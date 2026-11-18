<div align="center">

# Nguyen Mau Dung

High school senior (Class of 2027) in Ho Chi Minh City, Vietnam · applying to study **Actuarial Science** in the US

[![Email](https://img.shields.io/badge/nguyenmaudung79@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:nguyenmaudung79@gmail.com)
[![FinHub Tracker](https://img.shields.io/badge/FinHub_Tracker-live-1f6feb?style=flat-square&logo=vercel&logoColor=white)](https://finhubtracker-maudung.vercel.app/)
[![MathForge](https://img.shields.io/badge/MathForge-live-8957e5?style=flat-square&logo=vercel&logoColor=white)](https://mathforge-blush.vercel.app/)

</div>

My math teacher first suggested actuarial science to me in Grade 11. I love math, so I started
self-studying for the SOA exams, and in November 2026 I passed **SOA Exam P** (Probability;
preliminary result). **Exam FM** is next.

> **About the code here:** most of it was written by AI, mainly Claude. I choose what to build,
> decide what each app has to get right, test what comes back, and send it back when it is wrong.
> Because AI wrote the code, I can't assume an app is right just because it runs, so the projects
> are checked against answers that can be worked out by hand.

---

## Projects

### 📊 FinHub Tracker

[Live](https://finhubtracker-maudung.vercel.app/) ·
[Code](https://github.com/dung037517-netizen/finhub-tracker) ·
[The math](https://github.com/dung037517-netizen/finhub-tracker/blob/main/DERIVATION.md) ·
[Mistake log](https://github.com/dung037517-netizen/finhub-tracker/blob/main/POSTMORTEM.md)

A student finance planner that treats paying for college as a risk problem. It inflates costs
forward, saves month by month, pays the bills each semester, and runs 1,200 simulated market
paths. It shows the chance that the money runs out, not just one projected balance.

- In the sample plan, saving just enough for the *expected* return ($777 a month) still runs
  short in about half of the simulated futures. Reaching 90% confidence takes $1,090 a month,
  about 40% more. That extra amount is a **risk margin**.
  ([why it is about half](https://github.com/dung037517-netizen/finhub-tracker/blob/main/DERIVATION.md#44-why-funding-the-bel-leaves-50-ruin-probability))
- The savings math is tested against the annuity-due formula s̈ = [((1+i)ⁿ − 1)/i]·(1+i).
- It grew out of [FinanceFlow](https://github.com/dung037517-netizen/expense-tracker), my first
  finance app.

### 🧮 MathForge

[Live](https://mathforge-blush.vercel.app/) ·
[Code](https://github.com/dung037517-netizen/mathforge)

Calculus and statistics for the SAT and AP exams, solved step by step. Each solution names the
rule it uses, so the method is visible, not just the answer.

- Each AP problem notes where the same math shows up in actuarial work. The BC improper integral
  ∫₀^∞ e^(−0.05t) dt = 20 is the present value of a perpetuity, and an expected-value integral
  under constant mortality gives life expectancy, e̊ₓ = 1/μ.
- A survival-model lab (Gompertz, Makeham and others) shows the identity Ā + δā = 1 live on
  screen. If a calculation drifts, the number stops being 1, so the error is visible instead of
  hidden.

### ⠿ BrailleGuard AI

[Code](https://github.com/dung037517-netizen/braille-ai-jam-2026)

**AI-JAM US 2026: 9th of 840 entries from 41 countries, Silver Award (Healthcare).** It was my
idea, and I led a team of three. I built the app with AI tools.

One flattened Braille dot can turn PARACETAMOL into PARACETAMEL, and the person who relies on the
Braille is the one who can't check it against the print. BrailleGuard checks the Braille on
medicine packaging from a photo and holds the batch when it finds a defect. This repo is an MVP:
its inference engine is still simulated, and the README says so.

---

## How I build with AI

1. **Start from a real question.** Will the money be there when the bill arrives? Does the
   Braille say what the box says?
2. **Decide what "right" means before there is code:** a formula the result must match, a case
   the app must refuse.
3. **Let AI write it.** Then run it, use it, and send it back when something is off.
4. **Check numbers against answers worked out by hand,** not against the program's own earlier
   output.
5. **Write down what went wrong.**

Two mistakes these checks caught:

- FinHub's README once said 90% confidence costs **12%** more per month. The app said about 40%.
  The 12% came from old inputs and was never recomputed, so it was off by about three times. A
  test now guards that number.
  ([details](https://github.com/dung037517-netizen/finhub-tracker/blob/main/POSTMORTEM.md#mrm-001--published-risk-margin-understated-by-a-factor-of-three))
- A test expected an internal rate of return of 0.1289 for cash flows of −1000, +500 and +700.
  The code gave 0.1232. Solving 700v² + 500v − 1000 = 0 by hand gives i ≈ 0.1232, so the code
  was right and the test was wrong.
  ([details](https://github.com/dung037517-netizen/finhub-tracker/blob/main/POSTMORTEM.md#mrm-004--validation-oracle-was-itself-incorrect))

> I use AI the way an actuary uses a model: as a tool whose output is checked, not trusted.

---

## Toolkit

- **Math:** probability (SOA Exam P), calculus, statistics. This year: AP Calculus BC,
  AP Statistics, AP Microeconomics and AP Macroeconomics (exams in May 2027).
- **What the projects are built with:** TypeScript, Next.js, React, Python, Streamlit, Vitest.
- **Also:** Excel.

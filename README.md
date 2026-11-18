<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=170&section=header&text=Nguyen%20Mau%20Dung&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Actuarial%20Science%20applicant%20%C2%B7%20Class%20of%202027&descSize=16&descAlignY=58&animation=fadeIn" alt="Nguyen Mau Dung · Actuarial Science applicant · Class of 2027"/>

![SOA Exam P](https://img.shields.io/badge/SOA_Exam_P-passed_Nov_2026-2ea44f?style=flat-square)
![Next](https://img.shields.io/badge/next-Exam_FM-0e75b6?style=flat-square)
[![Email](https://img.shields.io/badge/nguyenmaudung79@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:nguyenmaudung79@gmail.com)

</div>

High school senior in Ho Chi Minh City, Vietnam. My math teacher suggested actuarial science to me in
Grade 11. I love math, so I started self-studying for the SOA exams and passed **Exam P** in November
2026 (preliminary result).

> [!NOTE]
> Most of the code here was written by AI, mainly Claude. I choose what to build, test what comes
> back, and send it back when it is wrong.

## 🚀 Projects

### 📊 FinHub Tracker &nbsp;[![live](https://img.shields.io/badge/live-1f6feb?style=flat-square&logo=vercel&logoColor=white)](https://finhubtracker-maudung.vercel.app/) [![code](https://img.shields.io/badge/code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dung037517-netizen/finhub-tracker) [![the math](https://img.shields.io/badge/the_math-0e75b6?style=flat-square)](https://github.com/dung037517-netizen/finhub-tracker/blob/main/DERIVATION.md)

Budgeting, savings goals and month-by-month cash flow for students, built on the real cost structure
of U.S. college applications. It shows what to be ready for in 9 out of 10 outcomes, not just the
expected total. A second page tests four years of college costs against 1,200 simulated market paths:
reaching 90% confidence costs about 40% more per month than saving for the expected return.

### 🧮 MathForge &nbsp;[![live](https://img.shields.io/badge/live-8957e5?style=flat-square&logo=vercel&logoColor=white)](https://mathforge-blush.vercel.app/) [![code](https://img.shields.io/badge/code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dung037517-netizen/mathforge) [![method](https://img.shields.io/badge/method-0e75b6?style=flat-square)](https://mathforge-blush.vercel.app/method)

SAT and AP math practice (algebra, calculus, statistics) built around a diagnose → practice → review
loop, with step-by-step solutions and a Digital-SAT-style mock test. Mastery estimates borrow from
actuarial credibility theory: a skill with little data is pulled toward related skills.

### ⠿ BrailleGuard AI &nbsp;[![code](https://img.shields.io/badge/code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dung037517-netizen/braille-ai-jam-2026)

**AI-JAM US 2026: 9th of 840 entries from 41 countries, Silver Award (Healthcare).** My idea; I led a
team of three and built it with AI tools. It checks the Braille on medicine packaging from a photo,
since one flattened dot turns PARACETAMOL into PARACETAMEL. A photo too blurry, dark or small to judge
goes to HUMAN REVIEW instead of being passed. MVP with a simulated inference engine.

## 🧾 How I build with AI

Real question → decide what "right" means → AI writes it → I run it and send it back → check against
hand-worked answers → write down what went wrong.

> I use AI the way an actuary uses a model: as a tool whose output is checked, not trusted.

<details>
<summary>Two mistakes these checks caught</summary>

- FinHub's README once said 90% confidence costs **12%** more; the app said about 40%. The 12% came
  from old inputs that were never recomputed. A test now guards it.
  ([details](https://github.com/dung037517-netizen/finhub-tracker/blob/main/POSTMORTEM.md#mrm-001--published-risk-margin-understated-by-a-factor-of-three))
- A test expected an IRR of 0.1289 for cash flows of −1000, +500 and +700; the code gave 0.1232.
  Solving 700v² + 500v − 1000 = 0 by hand gives i ≈ 0.1232, so the test was wrong, not the code.
  ([details](https://github.com/dung037517-netizen/finhub-tracker/blob/main/POSTMORTEM.md#mrm-004--validation-oracle-was-itself-incorrect))

</details>

## 🛠️ Toolkit

**Math:** probability (Exam P) · calculus · statistics · AP Calculus BC, AP Statistics, AP Micro and
Macro (exams May 2027)

**Projects built with:**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Built with Claude](https://img.shields.io/badge/built_with-Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" alt=""/>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Nguyen%20Mau%20Dung&fontSize=52&fontColor=ffffff&fontAlignY=35&desc=Pricing%20risk%20before%20I%20am%20old%20enough%20to%20underwrite%20it&descAlignY=55&descSize=17&animation=fadeIn" alt="banner"/>

<a href="https://github.com/dung037517">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3400&pause=900&color=38BDF8&center=true&vCenter=true&width=800&lines=Aspiring+Actuary+%26+Quantitative+Risk+Student;Applied+Mathematics+%7C+Probability+%7C+Financial+Risk+Modeling;Actuarial+Cash-Flow+Valuation+%26+Solvency+Analysis;Turning+uncertainty+into+a+number+someone+can+act+on" alt="Typing SVG" />
</a>

<br/>

**Nguyen Mau Dung** · *Dung Nguyen*

`Aspiring Actuary & Quantitative Risk Student` · `Applied Mathematics & Probability` · `Financial Risk Modeling`

<br/>

[![Live Demo — MathForge](https://img.shields.io/badge/🚀_Live_Demo-MathForge_·_SAT%2FAP_Calculus_Platform-8957e5?style=for-the-badge&labelColor=161b22)](https://mathforge-blush.vercel.app/)

[![Live Demo — FinHub Tracker](https://img.shields.io/badge/📊_Live_Demo-FinHub_Tracker_·_Student_Finance_Planner-1f6feb?style=for-the-badge&labelColor=161b22)](https://finhubtracker-maudung.vercel.app/)

<br/>

<img src="https://komarev.com/ghpvc/?username=dung037517&label=Profile%20views&color=0e75b6&style=flat-square" alt="profile views" />

</div>

---

## 🧭 About Me

I am interested in the question actuaries exist to answer: **given that the future is uncertain, how
much should we set aside today?**

Most of my work follows the same method, applied twice. Take a body of actuarial and financial
theory — survival models, annuity valuation, coherent risk measures, option pricing — implement it
**from its mathematical definition rather than from a library**, and then build an interface that
makes the model's assumptions visible to the person relying on it.

That constraint is deliberate. Calling a black-box function to get a reserve figure teaches you
nothing about whether the figure is defensible. Deriving the probit function yourself as a rational
approximation refined by a Halley step — then proving `Φ(Φ⁻¹(p)) = p` to ten decimal places in a
unit test — teaches you what the number actually means when it appears inside a Value-at-Risk
calculation.

**How I approach a risk problem**

- **A single number is usually a design failure.** If the honest answer is a distribution, reporting
  a point estimate hides exactly the information a decision-maker needs. Both of my models report
  percentiles, shortfall probabilities, and tail measures — not just an expected value.
- **Validate against closed form, never against yourself.** A model that only agrees with its own
  output proves nothing. Mine are pinned against analytic identities: `Āₓ = μ/(μ+δ)` under a
  constant force of mortality, `Āₓ + δ·āₓ = 1`, the annuity-due accumulation formula, and the
  textbook Black-Scholes price of 10.4506.
- **Show the identity that must hold.** Both platforms display a mathematical invariant live on
  screen. If the valuation logic breaks, the page says so rather than quietly producing a plausible
  number — which is the failure mode that actually matters in reserving work.

**Why Actuarial Science, and why in the United States**

I did not arrive at this field through a careers talk. I arrived at it by trying to answer a
concrete family question — *can we actually afford four years of university abroad?* — and
discovering that a spreadsheet could not answer it honestly. What the question needed was inflation
projection, an accumulation-then-decumulation cash-flow model, a stochastic return assumption, and a
solvency test. That is a **pension valuation in miniature**, and once I saw that structure, I began
to see it everywhere.

US actuarial programmes are where that instinct gets disciplined. I want to learn the professional
framework behind what I have been reconstructing on my own: reserving standards, risk margins,
capital adequacy, and why regulators such as Solvency II mandate **expected shortfall** rather than
Value at Risk — because TVaR is subadditive and VaR is not, so only one of them rewards
diversification honestly. I want to build models that a regulator could audit, not just models that
run.

---

## 🛠️ Technical & Quantitative Toolkit

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Actuarial & Quantitative Domains**

![Life Contingencies](https://img.shields.io/badge/Life_Contingencies-8957e5?style=for-the-badge)
![Survival Models](https://img.shields.io/badge/Survival_Models-0891b2?style=for-the-badge)
![Interest Theory](https://img.shields.io/badge/Interest_Theory-1f6feb?style=for-the-badge)
![Annuity Valuation](https://img.shields.io/badge/Annuity_Valuation-16a34a?style=for-the-badge)
![VaR & TVaR](https://img.shields.io/badge/VaR_%26_Expected_Shortfall-cf222e?style=for-the-badge)
![Monte Carlo](https://img.shields.io/badge/Monte_Carlo_Simulation-3fb950?style=for-the-badge)
![Option Pricing](https://img.shields.io/badge/Black--Scholes--Merton-db6d28?style=for-the-badge)
![Numerical Analysis](https://img.shields.io/badge/Numerical_Analysis-a855f7?style=for-the-badge)

**Modeling & Engineering**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Recharts](https://img.shields.io/badge/Data_Visualisation-22B5BF?style=for-the-badge&logo=chartdotjs&logoColor=white)
![KaTeX](https://img.shields.io/badge/LaTeX-329894?style=for-the-badge&logo=latex&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

## 📊 GitHub Statistics

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=dung037517&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=8957e5&text_color=c9d1d9" alt="GitHub Stats" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dung037517&layout=compact&langs_count=8&theme=radical&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=c9d1d9" alt="Top Languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=dung037517&theme=radical&hide_border=true&background=0D1117&ring=8957e5&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub Streak" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=dung037517&theme=radical&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="Trophies" />

</div>

---

## 🚀 Actuarial Modeling Projects

### 📈 FinHub Tracker — Student Finance Planning Web App

[![Live](https://img.shields.io/badge/Live_Demo-1f6feb?style=flat-square&logo=vercel&logoColor=white)](https://finhubtracker-maudung.vercel.app/)
[![Source](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dung037517-netizen/financeflow)
![Tests](https://img.shields.io/badge/tests-63_passing-3fb950?style=flat-square&logo=vitest&logoColor=white)
![Monte Carlo](https://img.shields.io/badge/Monte_Carlo-1200_futures-8957e5?style=flat-square)

> **Situation** — Preparing to study abroad forced my family to confront a question a spreadsheet
> could not answer honestly: given tuition inflation, market volatility, and four years of
> obligations, *what is the actual probability that the money runs out?* A point estimate of
> "roughly enough" is not an answer — it conceals precisely the uncertainty that matters.
>
> **Task** — Value the plan the way an actuary values a pension. Structurally it **is** one: an
> accumulation phase, a decumulation phase, an inflation assumption, a stochastic return assumption,
> and a solvency test at the end.
>
> **Action** — I built the valuation engine from its mathematical definitions, with no financial
> libraries:
> - Costs projected forward geometrically, `Cₖ = C₀(1+g)ᵏ`, against a college-inflation assumption
>   that historically outruns CPI.
> - Savings accumulated as an **annuity-due** with monthly compounding, `r_m = (1+r)^(1/12) − 1`,
>   then drawn down semester by semester as tuition bills fall due.
> - Because contributions and withdrawals **overlap**, no closed-form solution for the required
>   payment exists — so I solved it by **bisection on the minimum balance**, a quantity provably
>   monotone in the contribution, which guarantees the search converges instead of diverging.
> - **1,200-path Monte Carlo** over lognormal returns producing percentile fan bands, shortfall
>   probability, **expected shortfall**, and **VaR / TVaR** applied to a savings goal rather than a
>   trading book.
> - Beneath the planner sits a full risk desk: Value at Risk by four estimation methods (historical,
>   parametric, **Cornish-Fisher** corrected for skewness and excess kurtosis, and Monte Carlo), plus
>   **Black-Scholes-Merton** with an eight-Greek surface and bracketed-Newton implied volatility.
>
> **Result** — **63 unit tests**, including one pinning the savings ledger against the annuity-due
> closed form `s̈ₙ = [((1+i)ⁿ − 1)/i](1+i)` and one enforcing money conservation across the whole
> ledger. The model surfaced a genuinely counter-intuitive actuarial finding: **funding a plan to its
> *expected* return still leaves roughly a 50% chance of falling short**, because the median
> lognormal path sits below the arithmetic mean. Reaching 90% confidence costs **36–44% more per
> month** — and that gap *is* a **risk margin**, the same quantity that sits inside a technical
> provision. The option pricer displays its put-call parity residual live; it holds to
> **3.6 × 10⁻¹¹**.

---

### 🧮 MathForge — SAT/AP Calculus Learning Platform

[![Live](https://img.shields.io/badge/Live_Demo-8957e5?style=flat-square&logo=vercel&logoColor=white)](https://mathforge-blush.vercel.app/)
[![Source](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dung037517-netizen/mathforge)
![Tests](https://img.shields.io/badge/tests-48_passing-3fb950?style=flat-square&logo=vitest&logoColor=white)
![Deps](https://img.shields.io/badge/runtime_math_dependencies-0-f78166?style=flat-square)

> **Situation** — While teaching myself actuarial mathematics, I kept meeting the same obstacle from
> the opposite direction: online solvers returned answers and hid the reasoning. For actuarial work
> that is fatal — a reserve you cannot derive is a reserve you cannot defend, and the AP calculus
> underneath it is the same calculus that produces `āₓ` and an option's delta.
>
> **Task** — Build a platform that teaches the **derivation**, and implement the entire mathematical
> engine myself so that every step is something I understood well enough to write from scratch.
>
> **Action** — Hand-written computation core in strict TypeScript with zero uses of `any`:
> - A **recursive-descent parser** with character-level error positions, so a malformed formula
>   points a caret at the exact offending symbol.
> - A **symbolic differentiator** that names every rule it invokes — product, quotient, chain,
>   generalised power, and logarithmic differentiation for cases like `xˣ`.
> - **Adaptive Simpson quadrature** with Richardson extrapolation — the same routine that evaluates
>   `∫₀^π sin x dx = 2` for a calculus student also computes `Āₓ` for a whole-life policy.
> - **Five parametric mortality laws** (Gompertz, Makeham, De Moivre, Weibull, constant force) with
>   the full life-contingency stack derived from them: `ₜpₓ`, `e̊ₓ`, `Āₓ`, `āₓ`, and the net annual
>   premium by the equivalence principle.
> - Special functions built from their definitions: Lanczos log-gamma, regularised incomplete gamma
>   by series and continued fraction, `erf`/`erfc`, and the probit function.
> - A **Central Limit Theorem simulator** in a dedicated **Web Worker** — the theorem that explains
>   why an insurer can price a block of 10,000 policies far more confidently than a single one.
>
> **Result** — 12 exam-style AP Calculus AB/BC and AP Statistics problems, each annotated with the
> actuarial technique it becomes. **48 unit tests** pin the engine against analytic identities:
> `Āₓ = μ/(μ+δ)`, `āₓ = 1/(μ+δ)`, and `Āₓ + δ·āₓ = 1` for **Gompertz**, a law with no closed form on
> either side. The workbench displays that last identity live — it must equal exactly 1, so any
> quadrature error is visible on screen. The CLT panel reproduces the predicted `σ/√n` to within
> **0.70%**, and the page reaches interactive in **~0.95 s**.

---

## 🌱 Initiative & Independent Study

### Self-Directed Study in Actuarial Mathematics

> **Situation** — The material I wanted to model — survival distributions, life contingencies,
> coherent risk measures — sits far beyond any secondary school syllabus, and no course was going to
> cover it for me.
>
> **Task** — Learn enough probability theory and numerical analysis to implement actuarial models
> correctly, and *prove* I had rather than assume it.
>
> **Action** — I worked through each topic and implemented it from its definition, then tested
> against independently known results. When I built the complementary error function, I learned why
> it must be evaluated **directly by continued fraction** rather than as `1 − erf(x)`: the
> subtraction destroys floating-point precision in exactly the far tail that a 99% VaR figure depends
> on. When I implemented inverse-transform sampling of future lifetime `Tₓ`, I found a closed form
> for every mortality law except **Makeham** — whose mixed linear-plus-exponential hazard I inverted
> by bisection on the strictly increasing cumulative hazard.
>
> **Result** — A verified special-function and life-contingency library accurate to twelve decimal
> places, built without reference to an existing implementation, and validated by 40,000-draw
> sampling tests that reproduce the analytic `ₜpₓ` to within 1%.

### Open-Sourcing Both Models for Other Students

> **Situation** — The models solved my own problems, but neither problem is unique to me: classmates
> faced the same answer-only solvers, and other families applying abroad faced the same unquantified
> funding uncertainty.
>
> **Task** — Turn two personal models into work another student could pick up, **audit**, and trust —
> including the parts student projects usually skip.
>
> **Action** — I treated verifiability as a deliverable, not an afterthought: architecture diagrams,
> an explicit written mapping from each AP topic to its actuarial counterpart, and a stated policy
> that every numerical claim in the documentation is reproducible from a fixed random seed. I
> deliberately used **synthetic market data with fictitious tickers** rather than scraped prices, and
> said so plainly — implying a market-data licence I do not hold would be dishonest, and seeded data
> makes every published figure independently checkable.
>
> **Result** — Both repositories ship with zero build errors, zero lint warnings, zero uses of `any`,
> and **111 passing tests** between them. Anyone can clone either repository, run `npm test`, and
> confirm that the mathematics I claim is the mathematics that actually runs.

---

## 🎯 What I Am Working Toward

I am applying to study **Actuarial Science** in the United States. What draws me is the discipline's
central demand: that a number put forward as a reserve, a premium, or a capital requirement must be
**defensible to someone whose job is to challenge it**.

Concretely, I want to keep building models that:

- **Quantify uncertainty instead of hiding it.** The difference between "should be fine" and "fails
  one year in five" is the entire value an actuary adds.
- **Are honest about their assumptions.** Every parameter in my models is a visible, adjustable
  control, because an assumption a reader cannot see is an assumption they cannot challenge.
- **Are auditable by strangers.** Seeded randomness, closed-form test oracles, and on-screen identity
  checks, so that trusting the output never requires trusting me.

Longer term I intend to sit the professional examinations (**SOA Exam P** in probability and
**Exam FM** in financial mathematics), and to work where actuarial modeling meets computation —
pension and insurance valuation, capital modeling, and the reserving problems where getting the tail
right is the whole job.

---

## 📫 Contact

<div align="center">

[![Email](https://img.shields.io/badge/nguyenmaudung79@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nguyenmaudung79@gmail.com)
[![GitHub](https://img.shields.io/badge/@dung037517-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dung037517)

<br/>

[![MathForge](https://img.shields.io/badge/MathForge-Live-8957e5?style=flat-square&logo=vercel&logoColor=white)](https://mathforge-blush.vercel.app/)
[![FinHub Tracker](https://img.shields.io/badge/FinHub_Tracker-Live-1f6feb?style=flat-square&logo=vercel&logoColor=white)](https://finhubtracker-maudung.vercel.app/)

<br/>

*"The mathematics on an AP exam is the mathematics of risk — only the vocabulary changes."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" alt="footer"/>

</div>

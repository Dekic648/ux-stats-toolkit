# UX Research Statistics Toolkit

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Tools](https://img.shields.io/badge/Tools-12-1D9E75)](https://dekic648.github.io/ux-stats-toolkit/)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-7F77DD)](CONTRIBUTING.md)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222)](https://dekic648.github.io/ux-stats-toolkit/)

Free, open-source tools for researchers who want to get the stats right. No logins. No tracking. Just math.

**[Browse the toolkit →](https://dekic648.github.io/ux-stats-toolkit/)**

---

## What this is

A collection of 12 single-page tools that handle the statistics UX researchers actually need — sample sizing, confidence intervals, inter-rater reliability, severity calibration, and more. Each tool runs entirely in the browser with zero dependencies, zero back-end, and zero data collection.

The toolkit is organized into five chapters that follow the arc of a typical research project:

### 1. Planning

| Tool | What it does |
|------|-------------|
| [Sample Size Negotiator](https://dekic648.github.io/sample-size-negotiator/) | See exactly what coverage you get at any sample size — and generate a stakeholder explanation on the spot. |
| [Small n Capability Checker](https://dekic648.github.io/small-n-capability-checker/) | Check what your small sample can actually detect — before you promise stakeholders something your study can't deliver. |

### 2. Collecting & Coding

| Tool | What it does |
|------|-------------|
| [Behaviour Matrix + CI Builder](https://dekic648.github.io/behaviour-matrix-ci-builder/) | Log observed behaviours per task, compute success/failure rates, and get Adjusted-Wald confidence intervals in one matrix view. |
| [Inter-rater Reliability](https://dekic648.github.io/inter-rater-reliability/) | Calculate agreement between two raters using Cohen's Kappa and percent agreement — validate your coding scheme. |

### 3. Analyzing

| Tool | What it does |
|------|-------------|
| [Adjusted-Wald CI Builder](https://dekic648.github.io/adjusted-wald-ci-builder/) | Compute confidence intervals around task completion rates. Compares Adjusted-Wald, standard Wald, and LaPlace methods side by side. |
| [Which Statistical Test?](https://dekic648.github.io/which-statistical-test/) | Answer three questions. Get the right test for your data, why it was chosen, and what to avoid. |
| [Significance Translator](https://dekic648.github.io/significance-translator/) | Enter a p-value. Get plain English, a stakeholder sentence, and a list of what your result does and doesn't mean. |

### 4. Rating & Scoring

| Tool | What it does |
|------|-------------|
| [Severity Rating Calibrator](https://dekic648.github.io/severity-rating-calibrator/) | Rate usability problems with two frameworks (UserFocus + Nielsen) side by side and get a report-ready severity statement. |
| [Confidence Score Explainer](https://dekic648.github.io/confidence-score-explainer/) | Model the factors behind a finding's confidence score and generate a stakeholder-ready explanation. |
| [Qualitative Finding Strength Rater](https://dekic648.github.io/qualitative-finding-strength/) | Rate the evidential strength of qualitative findings using a structured rubric — move beyond gut-feel severity ratings. |

### 5. Reporting

| Tool | What it does |
|------|-------------|
| [Problem Discovery Estimator](https://dekic648.github.io/problem-discovery-estimator/) | Estimate how many usability problems remain undiscovered and how many more participants you need. |
| [Finding Uncertainty Communicator](https://dekic648.github.io/finding-uncertainty-communicator/) | Frame what you know, what you don't, and what you still need to find out — structured uncertainty reporting. |

---

## The Common Sense Guide

Not sure where to start? The toolkit includes a long-form narrative guide that walks through each chapter — what challenges researchers face, which tools address them, and when to reach for what.

**[Read the Common Sense Guide →](https://dekic648.github.io/ux-stats-toolkit/guide.html)**

---

## Design principles

- **Zero friction** — Every tool is a single HTML file. Open it, use it, close it.
- **No data leaves the browser** — All computation happens client-side. Nothing is sent anywhere.
- **Stakeholder-ready output** — Tools generate sentences and explanations you can paste directly into reports and presentations.
- **Opinionated defaults** — Based on established methods (Sauro & Lewis, Nielsen, Travis) so you don't have to look up the formulas yourself.

## Tech stack

Each tool is a standalone HTML file with inline CSS and vanilla JavaScript. No frameworks, no build steps, no package.json. Hosted on GitHub Pages with automated deployment via GitHub Actions.

## Who this is for

UX researchers, design teams, and anyone who runs usability studies and needs to back up their findings with the right statistics — without becoming a statistician.

## Contributing

This toolkit grows with contributions from the research community. Whether you want to propose a new tool, fix a bug, or improve an existing tool — you're welcome here.

- **[Propose a new tool](../../issues/new?template=new-tool.yml)** — Describe the research problem and the statistical method
- **[Report a bug](../../issues/new?template=bug-report.yml)** — Broken calculation? Layout issue? Let us know
- **[Read the full contributing guide](CONTRIBUTING.md)** — Setup, code style, and PR guidelines

No contribution is too small. Typo fixes, better explanations, mobile layout tweaks — it all makes the toolkit more useful for researchers.

## Author

Built by **Milo Vandekic** · Grounded in [Groundedly](https://groundedly.vercel.app)

## License

MIT

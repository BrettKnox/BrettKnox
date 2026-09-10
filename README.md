# Brett Knox

**Data Science · Machine Learning · Systems Engineering**

I build things that run on hardware people already own, and I measure them instead of
claiming them. Most of what is here has a number attached, and the number came from a
run, not an estimate.

[![Portfolio](https://img.shields.io/badge/Portfolio-wukoric.com-1f6feb?style=flat-square)](https://wukoric.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-brettwknox-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/brettwknox)
[![Email](https://img.shields.io/badge/Email-brettknox2003%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:BrettKnox2003@gmail.com)

---

## Current work

| Project | What it is | The number |
|---|---|---|
| [**open-problems-lab**](https://github.com/BrettKnox/open-problems-lab) | 12 open problems in maths and computational theory, each with a machine-checked Lean 4 statement that CI compiles | First known formalization of **integer complexity**, no `sorry`; ‖2ⁿ‖ = 2n **proved for n ≤ 9**; **no odd covering system has lcm ≤ 10⁶** |
| [**vkgrad**](https://github.com/BrettKnox/vkgrad) | A training stack for GPUs that are not NVIDIA, built on Vulkan compute. Cooperative matrix was already used for inference; this runs a backward pass on it | A **315.4M-parameter** transformer trains on an integrated laptop GPU in **7.31 GiB**, no CUDA and no ROCm. MNIST to **97.6%**, **5.3x** faster than the CPU sharing the same die ([5 runs, ranges recorded](https://github.com/BrettKnox/vkgrad/blob/master/bench/mnist-repro.json)) |
| [**cue**](https://github.com/BrettKnox/cue) | Live transcription and recall for conversations. The audio never leaves the phone: it asks for the on-device recogniser by name and refuses to record rather than fall back to a cloud one | Accessibility audit drives the app across **54 screen states**, asserting touch targets, contrast against the real composited backdrop, and accessible names. [**0 failures**](https://github.com/BrettKnox/cue/blob/master/docs/audit-result.json), and the audit is proven to fail |

---

## Selected earlier work

### Silent De-escalation in the ICU · [`silent-icu-shifts`](https://github.com/BrettKnox/silent-icu-shifts)

> **MIMIC-IV Datathon 2026**: multi-institutional research collaboration

Detecting when ICU care teams quietly shift toward comfort care before the chart ever
reflects it. Across 94,000+ ICU stays in MIMIC-IV, the project builds a *Palliative-ness
Score*: a residualized composite of lab velocity, diagnostic diversity, clinical
engagement, and specialist integration, to surface a behavioral gap standard quality
audits miss.

- Temporal bin features (3 × 24h windows plus bin-to-bin deltas) over the full cohort in BigQuery and DuckDB
- **1,217 silent candidates** identified (2.8% of the never-transition population) whose care patterns match the palliative signature with no formal order on record
- XGBoost, Random Forest, Ridge and Lasso evaluated for long-stay prediction (≥ 21 days); XGBoost reached **AUPRC 0.557** on a held-out 20% partition
- Behavioral signal leads formal documentation by **~48 hours**, with 42% of the de-escalation shift occurring before any chart update

### Predicting Poor Mental Health at the District Level · [`vulnerability-dashboard`](https://github.com/BrettKnox/vulnerability-dashboard)

> CAP 4922 Data Science Capstone · University of North Florida

239 city council districts across 14 US cities, predicted from socioeconomic,
environmental and healthcare-access indicators.

- Ridge with city fixed effects reached **CV R² = 0.903** (RMSE 0.75). City dummies alone moved R² from ~0.70 to 0.93, which is itself the finding: unmeasured local context dominates
- PCA-weighted composite risk index (0-100) over 4 components, final index r = 0.688 (p < 0.001)
- **Leave-One-City-Out CV** to test cross-city generalization, which exposed where it breaks (Miami, Nashville)
- Interactive D3.js choropleth with cluster toggle, risk slider, rankings and CSV upload

---

## Stack

| Languages | Data | Tools | Areas |
|---|---|---|---|
| Python · Java · SQL · Lean 4 | PostgreSQL · DuckDB · BigQuery · SQLite | Git · React Native · Vulkan · Cloudflare Workers | ML pipelines · statistical modelling · formal verification · accessibility · concurrent systems |

---

## What I care about

Measuring rather than guessing. An accessibility audit that has never been seen failing
proves nothing, so mine is deliberately broken first. A benchmark extrapolated from best-case
step times gets re-run for twelve minutes to find out it was 7% optimistic. A privacy claim
gets checked against the network calls the app actually makes.

<sub><a href="mailto:BrettKnox2003@gmail.com">BrettKnox2003@gmail.com</a> · <a href="https://linkedin.com/in/brettwknox">linkedin.com/in/brettwknox</a> · <a href="https://wukoric.com">wukoric.com</a></sub>

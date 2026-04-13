<div align="center">

```
██████╗ ██████╗ ███████╗████████╗████████╗    ██╗  ██╗███╗   ██╗ ██████╗ ██╗  ██╗
██╔══██╗██╔══██╗██╔════╝╚══██╔══╝╚══██╔══╝    ██║ ██╔╝████╗  ██║██╔═══██╗╚██╗██╔╝
██████╔╝██████╔╝█████╗     ██║      ██║       █████╔╝ ██╔██╗ ██║██║   ██║ ╚███╔╝
██╔══██╗██╔══██╗██╔══╝     ██║      ██║       ██╔═██╗ ██║╚██╗██║██║   ██║ ██╔██╗
██████╔╝██║  ██║███████╗   ██║      ██║       ██║  ██╗██║ ╚████║╚██████╔╝██╔╝ ██╗
╚═════╝ ╚═╝  ╚═╝╚══════╝   ╚═╝      ╚═╝       ╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝  ╚═╝
```

### Data Science · Machine Learning · Systems Engineering

[![LinkedIn](https://img.shields.io/badge/LinkedIn-brettwknox-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/brettwknox)
[![Email](https://img.shields.io/badge/Email-brettknox2003%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:BrettKnox2003@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-BrettKnox-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/BrettKnox)

*I build reproducible machine learning systems, structured data pipelines,*
*and performance-driven software.*

</div>

---

## Featured Projects

---

### 🏥 Silent De-escalation in the ICU ·  [`silent-icu-shifts`](https://github.com/BrettKnox/silent-icu-shifts)

> **MIMIC-IV Datathon 2026** — multi-institutional research collaboration

Detecting when ICU care teams quietly shift toward comfort care before the chart ever reflects it. Working across 94,000+ ICU stays in MIMIC-IV, the project builds a novel *Palliative-ness Score* — a residualized composite of lab velocity, diagnostic diversity, clinical engagement, and specialist integration — to surface a behavioral gap that standard quality audits miss entirely.

- Engineered temporal bin features (3 × 24h windows + bin-to-bin deltas) over the full MIMIC-IV cohort using BigQuery and DuckDB
- Identified **1,217 silent candidates** (2.8% of never-transition population) whose care patterns match the palliative signature with no formal order on record
- Built and evaluated XGBoost, Random Forest, Ridge, and Lasso pipelines for long-stay prediction (≥ 21 days); XGBoost achieved **AUPRC 0.557** on a held-out 20% partition
- Validated behavioral signal leads formal documentation by **~48 hours**, with 42% of the total de-escalation shift occurring before any chart update

[![Python](https://img.shields.io/badge/Python-3.8-1a1a2e?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![XGBoost](https://img.shields.io/badge/XGBoost-best_model-e07b39?style=flat-square)](https://xgboost.readthedocs.io/)
[![MIMIC-IV](https://img.shields.io/badge/Data-MIMIC--IV_v3.1-0a3f6e?style=flat-square)](https://physionet.org/content/mimiciv/)
[![DuckDB](https://img.shields.io/badge/Engine-DuckDB-ffd700?style=flat-square)](https://duckdb.org)

---

### ☕ Coffee Quality ML Pipeline · [`Coffee-Quality-Kaggle`](https://github.com/BrettKnox/Coffee-Quality-Kaggle)

Full end-to-end ML workflow — preprocessing, feature selection, cross-validation, and model benchmarking across KNN, Random Forest, Logistic Regression, AdaBoost, and baselines. Structured for reproducibility and controlled evaluation.

[![Python](https://img.shields.io/badge/Python-grey?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-grey?style=flat-square&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)

---

### 🎧 Audio CRNN Deep Learning 

Preprocessing pipeline converting raw audio into spectrogram representations, fed into Convolutional Recurrent Neural Networks. Evaluated the generalization impact of different preprocessing strategies with structured accuracy analysis.

[![PyTorch](https://img.shields.io/badge/PyTorch-grey?style=flat-square&logo=pytorch&logoColor=white)]()

---

### 🛒 PostgreSQL E-Commerce Application · [`Eccomerce-App`](https://github.com/BrettKnox/Eccomerce-App)

Normalized relational schema with indexing, triggers, and stored logic. Built a validated query interface and improved performance using execution plan analysis.

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-grey?style=flat-square&logo=postgresql&logoColor=white)](https://postgresql.org)
[![SQL](https://img.shields.io/badge/SQL-grey?style=flat-square)]()

---

### ⚡ Concurrent Socket Server Benchmarking · [`Concurrent-Socket-Server`](https://github.com/BrettKnox/Concurrent-Socket-Server)

Iterative and multithreaded servers handling concurrent client requests. Measured latency, throughput, and scaling behavior under load — focused on where the performance actually breaks.

[![Java](https://img.shields.io/badge/Java-grey?style=flat-square&logo=openjdk&logoColor=white)]()

---

## Stack

<div align="center">

| Languages | Databases | Tools & Platforms | Concepts |
|:---:|:---:|:---:|:---:|
| Python · Java · SQL | PostgreSQL · DuckDB | Git · Google Colab | ML Pipelines |
| R · SAS · MATLAB | BigQuery | VSCode · MATLAB | Statistical Modeling |
| | | | Concurrent Systems |

</div>

---

## Current Focus

```
  ┌─────────────────────────────────────────────────────┐
  │  Advanced ML system design                          │
  │  Model evaluation frameworks                        │
  │  Large-scale experiment structuring                 │
  │  Performance-conscious software architecture        │
  └─────────────────────────────────────────────────────┘
```

---

<div align="center">
<sub>
  <a href="mailto:BrettKnox2003@gmail.com">BrettKnox2003@gmail.com</a>
  · 
  <a href="https://linkedin.com/in/brettwknox">linkedin.com/in/brettwknox</a>
</sub>
</div>

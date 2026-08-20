<h1 align="center">Hi, I'm Smitkumar Velani</h1>
<h3 align="center">MS Data Science @ Northeastern University, Boston</h3>
<p align="center">Causal Inference · LLM Evaluation · MLOps · Seeking Jan 2027 DS Co-op</p>

<p align="center">
  <a href="https://www.linkedin.com/in/smit-velani"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="https://smit-velani.github.io"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=github&logoColor=white"/></a>
  <a href="mailto:velani.sm@northeastern.edu"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Boston%2C%20MA-4285F4?style=flat&logo=google-maps&logoColor=white"/>
</p>

---

I build ML systems and then try to prove they work. Most of what I find interesting sits in the gap between a model producing a number and anyone having reason to trust it — validation harnesses, assumption diagnostics, evaluation of the evaluators.

**MS Data Science, Northeastern University** · GPA 4.0/4.0 · Boston
**B.E. Information & Communication Technology**, Adani University · CGPA 8.24/10

---

## Featured Work

### 🔬 [CausalLens](https://github.com/Smit-Velani/causal-lens) · [Live Demo](https://causal-lens-smit.streamlit.app)
**Causal inference and experimentation platform.** CUPED, DiD, PSM, doubly robust AIPW, Bayesian A/B, uplift modelling, and always-valid sequential inference — each validated against a known injected effect, each shipping its own assumption diagnostic.

The result I like most: a placebo test measured a +0.45/period pre-trend from pre-treatment data alone and predicted the realised DiD bias of 0.37. Validated externally on the LaLonde benchmark, recovering \$1,637 against a \$1,794 experimental truth from a −\$8,498 naive baseline.

`Python` `Statsmodels` `Scikit-Learn` `SciPy` `Streamlit` · 45 tests · GitHub Actions

---

### 🔭 [AgentAudit](https://github.com/Smit-Velani/agent-audit) · [Live Demo](https://agentaudit-scout.streamlit.app)
**AI agent evaluation harness** built around Scout, a ReAct-style CSV analyst with dual LLM-as-judge validation.

Cohen's κ = 0.774 judge-vs-human agreement (95% CI 0.46–1.00). A deliberately introduced operator swap dropped the pass rate 83% → 50%, caught by regression checks. Red-teaming exposed a hallucination that keyword guardrails could not see, so I built a grounding guardrail that validates entity mentions against the dataset itself.

`Python` `LangChain` `LangGraph` `Groq GPT-OSS` `Streamlit` · 23 tests · GitHub Actions

---

### 🧊 [GlassBox ML](https://github.com/Smit-Velani/glassbox-ml)
**Full-stack AutoML platform.** Upload any CSV; it inspects data quality, flags target leakage, infers the problem type, trains five model families, and writes an AI-generated PDF report.

Selects the winning model by expected business cost rather than raw accuracy — on 284K-row fraud data it chose XGBoost over Logistic Regression despite comparable AUC-ROC, because LR's 0.06 precision was ruinously expensive. AUC-ROC 0.981, AUC-PR 0.848.

`FastAPI` `React` `XGBoost` `SHAP` `LIME` `Groq GPT-OSS` · 14 tests · GitHub Actions

---

## Also Built

| Project | What it does |
|---|---|
| [Global Economic Intelligence Dashboard](https://github.com/Smit-Velani/Global-Economic-Intelligence-Dashboard) | Real-time platform for 190+ countries — ARIMA forecasting, K-Means clustering, VADER sentiment, live WebSocket updates |
| [DailyBrief AI](https://github.com/Smit-Velani/dailybrief-ai) | 6-layer pipeline reading Gmail and Calendar, delivering a personalised brief 3× daily, deployed 24/7 |
| [Multi-Agent Atari Boxing DQN](https://github.com/Smit-Velani/Multi-Agent-Atari-Boxing-DQN) | Two DQN agents learning to compete from raw pixels — CNN, frame stacking, experience replay |
| [Loan Default Prediction](https://github.com/Smit-Velani/Loan-Default-Prediction-MLflow) | 32,581 credit records, 4 models tracked in MLflow — XGBoost at 0.947 AUC |
| [RAG PDF Chatbot](https://github.com/Smit-Velani/RAG-PDF-Chatbot) | FAISS retrieval over any uploaded PDF, with honest refusal when the answer isn't in the document |
| [DataPulse Dashboard](https://github.com/Smit-Velani/datapulse-dashboard) | 11,900+ records across three domains, 7 D3.js chart types, fully client-side |

---

## Experience

**Data Analyst Intern** — Unified Mentor Pvt. Ltd. · Jan–Apr 2025
Built an equities analytics platform end to end: 11 indicator and return series from vectorised NumPy with no TA library, risk profiling via Sharpe ratio and max drawdown, surfaced through a 20-chart interactive dashboard.

**Data Analytics Intern** — IBM SkillsBuild (CSRBOX) · Jun–Aug 2024
Sole engineer on a crop-disease diagnostic system. MobileNetV2 transfer learning at 89% accuracy across 15 disease classes and 16,500+ images, served through a Flask app with an OpenCV feature-extraction pipeline.

---

## Stack

**Languages** Python · SQL · JavaScript
**ML** Scikit-Learn · XGBoost · PyTorch · TensorFlow · SHAP · LIME · Statsmodels
**LLM** LangChain · LangGraph · FAISS · Groq
**Data** Pandas · NumPy · MongoDB · PostgreSQL · MLflow
**Viz** Plotly · D3.js · Matplotlib · Streamlit
**Infra** FastAPI · Flask · React · Git · GitHub Actions

---

<p align="center">
  <i>Open to Data Science Co-op opportunities for January 2027 in Boston</i>
</p>

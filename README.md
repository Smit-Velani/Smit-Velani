<h1 align="center">Smit Velani</h1>
<h3 align="center">MS Data Science @ Northeastern University, Boston</h3>
<p align="center">Causal Inference · LLM Evaluation · MLOps · Seeking Jan 2027 DS Co-op</p>

<p align="center">
  <a href="https://smit-velani.github.io"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=githubpages&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/smit-velani"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:velani.sm@northeastern.edu"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Boston%2C%20MA-4285F4?style=flat&logo=google-maps&logoColor=white"/>
</p>

<p align="center">
  <b>Portfolio →</b> <a href="https://smit-velani.github.io">smit-velani.github.io</a>
</p>

---

I build ML systems and then try to prove they work. Most of what interests me sits in the gap between a model producing a number and anyone having reason to trust it — validation harnesses, assumption diagnostics, and evaluating the evaluators.

---

## Education

**Northeastern University**, Boston, MA — MS Data Science · 2026–2028
**Adani Institute of Infrastructure Engineering (GTU)** — B.E. Information & Communication Technology · 2021–2025

---

## Experience

**Data Science Intern** — Unified Mentor Pvt. Ltd. · Jan–Apr 2025
- Owned full-cycle delivery of an equities analytics platform covering ingestion, indicator engine, risk metrics and dashboard, built on Pandas, NumPy and yfinance
- Engineered 11 technical indicators from scratch (SMA, EMA, Bollinger Bands, RSI, MACD, ATR) using fully vectorised NumPy with no external TA library
- Computed Sharpe Ratio, Max Drawdown, annualised volatility, skewness and kurtosis for risk-return profiling, surfaced through a 20-chart interactive dashboard

**Data Science Intern** — IBM SkillsBuild (CSRBOX) · Jun–Aug 2024
- Sole engineer on a crop-disease diagnostic system across 15 disease classes and 16,500+ PlantVillage images
- Deployed a MobileNetV2 transfer-learning CNN at 89% accuracy via two-phase fine-tuning of the top 50 layers
- Shipped a Flask web app with drag-and-drop input for real-time inference, backed by an OpenCV pipeline extracting 6 visual features per image

---

## Projects

### 🔬 [CausalLens](https://github.com/Smit-Velani/causal-lens) · [Live Demo](https://causal-lens-smit.streamlit.app)
*Causal Inference and Experimentation Platform · Python, Statsmodels, Scikit-Learn, SciPy, Streamlit*

- Architected a causal inference platform implementing CUPED, DiD, PSM, doubly robust AIPW, Bayesian A/B testing and T-Learner uplift, across randomized and observational data
- Reduced confounding bias from 1.82 (naive) to −0.16 with PSM and −0.05 with AIPW across 30 random seeds, and trimmed outcome variance 47.2% under CUPED without shifting the point estimate
- Validated on the LaLonde NSW benchmark, recovering 1,637 USD from a −8,498 USD naive baseline against 1,794 USD truth, and 128.4% AUUC on 223K-row Criteo · 45 of 45 pytest
- Built a DiD placebo test measuring a 0.45 per period pre-trend that predicted the realized 0.37 bias, and a pipeline-refitting bootstrap exposing 58% understated standard error in the PSM interval

---

### 🔭 [AgentAudit](https://github.com/Smit-Velani/agent-audit) · [Live Demo](https://agentaudit-scout.streamlit.app)
*AI Agent Evaluation and LLM Safety · Python, LangChain, LangGraph, Groq, Scikit-Learn, Streamlit*

- Measured Cohen's kappa 0.774 judge-vs-human agreement (95% CI 0.46 to 1.00, n=15) for an evaluation harness wrapped around Scout, a ReAct-style CSV analyst, validating dual LLM-as-judge graders on a 29-task golden set
- Caught a silent operator-swap bug through automated regression checks; pass rate fell from 83% to 50% and a red-team sweep cut unsafe responses from 86% to 57% post-guardrail, reproducing exactly after a mid-project model migration
- Closed the hallucination gap the red team exposed with a grounding guardrail validating entity mentions against the dataset, catching invented categories two keyword filters missed · deployed publicly, 23 of 23 pytest

---

### 🧊 [GlassBox ML](https://github.com/Smit-Velani/glassbox-ml)
*AutoML, MLOps, Full-Stack · Python, FastAPI, React, XGBoost, SHAP, Groq, MLflow*

- Consolidated repetitive ML setup into a full-stack AutoML system that inspects data quality, flags target leakage, infers problem type and trains multiple model families unattended
- Designed cost-aware model selection around a configurable business cost matrix with a recall-floor guardrail, leakage-free SMOTE cross-validation and adaptive SHAP explainers for tree, linear and kernel architectures
- Reached AUC-ROC 0.981 and AUC-PR 0.848 on a 284K-row fraud benchmark, compressing training time from 20 to 3 min under dynamic scaling, plus PSI drift detection and 14 pytest tests wired into CI

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

## Technical Skills

**Languages** — Python, SQL, JavaScript

**ML & Statistics** — XGBoost, SHAP, AutoML, Causal Inference (CUPED, DiD, PSM, AIPW), A/B Testing, LLM Evaluation, RAG, K-Means, ARIMA, Anomaly Detection

**Libraries** — Pandas, NumPy, Scikit-Learn, Statsmodels, PyTorch, TensorFlow, LangChain, FastAPI, Flask, Streamlit

**Data & Infra** — PostgreSQL, MongoDB, MLflow, FAISS, Git, GitHub Actions

**Computer Vision & Viz** — OpenCV, CNN, Transfer Learning, Matplotlib, Seaborn, Plotly

---

<p align="center">
  <i>Open to Data Science Co-op opportunities for January 2027 in Boston</i>
</p>

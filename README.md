
<h1 align="center">Smit Velani</h1>

<h3 align="center">MS Data Science @ Northeastern University, Boston</h3>

<p align="center">
AI/ML Engineering · Agentic AI · LLM Evaluation · MLOps · Causal Inference
</p>

<p align="center">
  <a href="https://smit-velani.github.io">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=githubpages&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/smit-velani">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:velani.sm@northeastern.edu">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Boston%2C%20MA-4285F4?style=flat&logo=google-maps&logoColor=white"/>
</p>

<p align="center">
  <b>Portfolio →</b>
  <a href="https://smit-velani.github.io">smit-velani.github.io</a>
</p>

---

I build AI and machine learning systems with an emphasis on **evaluation, reliability, and real-world deployment**. I am especially interested in the gap between a model producing an output and having enough evidence to trust that output — evaluation frameworks, failure analysis, data validation, experimentation, monitoring, and reproducibility.

My work spans **agentic AI, LLM evaluation, MLOps, causal inference, computer vision, predictive modeling, and data engineering**. Across internships and independent projects, I have built systems ranging from automated ML pipelines and real-time computer vision applications to tool-using AI agents and statistical experimentation platforms.

Currently pursuing an **M.S. in Data Science at Northeastern University** and seeking **Spring 2027 AI/ML Engineering, Data Science, Applied AI, and MLOps co-op opportunities in Boston/Cambridge**.

---

## Education

**Northeastern University**, Boston, MA  
M.S. Data Science · 2026–2028

**Adani Institute of Infrastructure Engineering (GTU)**, India  
B.E. Information & Communication Technology · 2021–2025

---

## Experience

**Data Science Intern** — Simform Solutions · Jun–Sep 2025

- Engineered an end-to-end ML pipeline processing **10K+ daily records**, automating data cleaning, validation, feature engineering, aggregation, and anomaly detection
- Developed and evaluated ML models using feature selection, hyperparameter tuning, and cross-validation, measuring performance with precision, recall, F1, and ROC-AUC
- Built automated data-quality and model-evaluation workflows to detect invalid inputs and performance deviations while producing reliable outputs for downstream analytics

**Data Science Intern** — Unified Mentor Pvt. Ltd. · Jan–Apr 2025

- Built an end-to-end equities analytics platform covering SQL/API ingestion, quantitative computation, risk analysis, and interactive reporting
- Engineered **11 quantitative indicators and metrics** using vectorized Python and NumPy, including SMA, EMA, Bollinger Bands, RSI, MACD, ATR, Sharpe Ratio, Max Drawdown, and annualized volatility
- Developed a **20-chart analytics dashboard** for trend, correlation, and risk-return analysis and communicated findings to non-technical stakeholders

**Data Science Intern** — IBM · Jun–Aug 2024

- Developed an end-to-end computer vision system across **15 classes and 16,500+ images**
- Fine-tuned MobileNetV2 using transfer learning to achieve **89% classification accuracy**
- Deployed real-time inference with Python, Flask, and OpenCV, engineering **six quantitative visual features** for interpretable predictions

---

## Projects

### 🔬 [CausalLens](https://github.com/Smit-Velani/causal-lens) · [Live Demo](https://causal-lens-smit.streamlit.app)

*Experimentation & Causal Inference · Python, Statsmodels, Scikit-Learn, SciPy, Streamlit*

- Built a causal inference platform implementing **CUPED, Difference-in-Differences, PSM, doubly robust AIPW, Bayesian A/B testing, and T-Learner uplift modeling**
- Reduced estimated confounding bias from **1.82 naive → -0.16 PSM → -0.05 AIPW** across 30 random seeds and reduced outcome variance **47.2% with CUPED**
- Validated on the LaLonde NSW benchmark, recovering **$1,637 vs. $1,794 ground truth** from a **-$8,498 naive estimate**, and achieved **128.4% AUUC** on the 223K-row Criteo uplift dataset
- Built placebo and bootstrap diagnostics for identifying pre-trend bias and understated uncertainty, backed by **45/45 passing pytest tests**

---

### 🔭 [AgentAudit](https://github.com/Smit-Velani/agent-audit) · [Live Demo](https://agentaudit-scout.streamlit.app)

*Agentic AI & LLM Evaluation · Python, LangChain, LangGraph, Scikit-Learn, Streamlit*

- Built a **ReAct-style agent evaluation framework** with multi-step tool calling, trace logging, grounding validation, guardrails, and automated regression testing
- Measured **0.774 Cohen's kappa** judge-human agreement and built evaluation workflows for systematically analyzing agent accuracy, reliability, safety, and failure modes
- Reduced unsafe responses from **86% to 57%** through guardrails and implemented grounding validation to detect hallucinated entities missed by keyword-based checks
- Built repeatable offline evaluation and regression infrastructure backed by **23/23 passing pytest tests**

---

### 🧊 [GlassBox ML](https://github.com/Smit-Velani/glassbox-ml)

*Automated ML & MLOps · Python, FastAPI, XGBoost, SHAP, MLflow, Docker*

- Built an end-to-end ML platform spanning **data profiling, leakage detection, automated problem inference, feature processing, model training, evaluation, explainability, and monitoring**
- Designed cost-aware model selection with configurable business costs, a recall-floor guardrail, leakage-free SMOTE cross-validation, and adaptive SHAP explainability
- Achieved **0.981 ROC-AUC and 0.848 PR-AUC** on a 284K-row fraud benchmark while reducing training time from **20 to 3 minutes**
- Added PSI drift detection, MLflow experiment tracking, Docker packaging, and **14-test pytest CI/CD**

---

## Also Built

| Project | What it does |
|---|---|
| [Global Economic Intelligence Dashboard](https://github.com/Smit-Velani/Global-Economic-Intelligence-Dashboard) | Real-time economic intelligence across 190+ countries using ARIMA forecasting, K-Means clustering, Isolation Forest anomaly detection, sentiment analysis, WebSockets, and D3.js |
| [DailyBrief AI](https://github.com/Smit-Velani/dailybrief-ai) | Multi-stage AI workflow integrating Gmail and Calendar data to generate personalized daily briefings |
| [Multi-Agent Atari Boxing DQN](https://github.com/Smit-Velani/Multi-Agent-Atari-Boxing-DQN) | Two reinforcement-learning agents trained from raw visual observations using CNNs, frame stacking, and experience replay |
| [Loan Default Prediction](https://github.com/Smit-Velani/Loan-Default-Prediction-MLflow) | ML experimentation across 32,581 credit records with four tracked models and XGBoost reaching 0.947 ROC-AUC |
| [RAG PDF Chatbot](https://github.com/Smit-Velani/RAG-PDF-Chatbot) | Retrieval-augmented PDF question answering using FAISS with grounded response behavior |
| [DataPulse Dashboard](https://github.com/Smit-Velani/datapulse-dashboard) | Interactive analytics dashboard covering 11,900+ records across three domains with seven D3.js visualization types |

---

## Technical Skills

**Languages** — Python, SQL, R, JavaScript, TypeScript, C++, Java, C#, Go, Bash

**AI & Machine Learning** — Scikit-Learn, XGBoost, PyTorch, TensorFlow, Keras, Deep Learning, CNNs, Transfer Learning, Feature Engineering, Anomaly Detection

**Agentic AI & LLM Systems** — LLMs, AI Agents, Agentic AI, RAG, LangChain, LangGraph, FAISS, Tool Calling, Tool Execution, Guardrails, LLM Evaluation

**Statistics & Experimentation** — Causal Inference, CUPED, DiD, PSM, AIPW, A/B Testing, Bayesian Inference, Hypothesis Testing, Time Series, Forecasting, Statistical Modeling

**Data Engineering & Analytics** — Pandas, NumPy, SciPy, Statsmodels, Spark, PySpark, Databricks, PostgreSQL, MySQL, MongoDB, Excel, Power BI

**MLOps & Engineering** — MLflow, SHAP, FastAPI, Flask, REST APIs, AWS, Docker, Kubernetes, Terraform, Redis, GitHub Actions, CI/CD, pytest, Git, Linux

**Visualization** — Matplotlib, Seaborn, Plotly, D3.js

---

<p align="center">
  <b>Open to Spring 2027 Co-op opportunities in AI/ML Engineering, Data Science, Applied AI, Agentic AI, and MLOps</b>
</p>

<p align="center">
  Boston / Cambridge, MA
</p>

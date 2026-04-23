<h2 align="left">Leonardo León 👨‍💻</h2>
<h3 align="left">Backend Developer · Python · DevOps · Banking Systems · AI Integration</h3>

<p align="left">
  <em>Building production-grade financial tools and automation systems — one project at a time.</em>

<p align="center">
  <img src="https://img.shields.io/badge/Python-26408B?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash_Script-555EAD?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-1F3F7A?style=for-the-badge&logo=postgresql&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/AI_&_LLMs-C4A35A?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Arch_Linux-3D5A99?style=for-the-badge&logo=archlinux&logoColor=white" />
  <img src="https://img.shields.io/badge/WSL2-4A4580?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-1A3A6B?style=for-the-badge&logo=docker&logoColor=white" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=korearn&theme=dracula" height="150" alt="streak graph" />
</p>

<p align="center">
  <img src="github-metrics.svg" alt="Metrics" style="max-width: 100%; height: auto;" />
</p>

## 🏦 Fintech & Banking Portfolio

> A structured series of 8 production-inspired projects targeting Backend, DevOps, and AI roles in financial environments.

| # | Project | Stack | Highlights |
|---|---------|-------|------------|
| 1 | [TX-Classifier](https://github.com/korearn/tx-classifier) | Python · SQLite · LMStudio | NLP transaction categorization |
| 2 | [Bank Reconciliation](https://github.com/korearn/bank-reconciliation) | Python · Pandas · Bash | Automated discrepancy detection |
| 3 | [Exchange Rate API](https://github.com/korearn/exchange-rate-api) | FastAPI · SQLite · Docker | REST microservice with cache |
| 4 | [Infra Monitor](https://github.com/korearn/infra-monitor) | psutil · Bash · LMStudio | AI-powered system monitoring |
| 5 | [ETL Pipeline](https://github.com/korearn/etl-pipeline) | PostgreSQL · Pandas · Cron | Financial & weather data pipeline |
| 6 | [Credit Scoring API](https://github.com/korearn/credit-scoring-api) | scikit-learn · FastAPI · LMStudio | ML scoring with XAI |
| 7 | [Financial RAG Assistant](https://github.com/korearn/financial-rag) | ChromaDB · sentence-transformers · LMStudio | Document Q&A with RAG |

---

### ✅ [TX-Classifier — Transaction Classifier](https://github.com/korearn/tx-classifier)
**Automatic NLP-based bank transaction categorization using local LLMs**
`Python` `SQLite` `LMStudio` `Pandas` `Rich` `Prompt Engineering`
- Classifies bank transactions from CSV using a local LLM (Qwen2.5 / Gemma 3) via LMStudio
- Stores results in SQLite with category analytics via SQL aggregations
- 100% private — no external APIs, no data leaves the machine

### ✅ [Bank Reconciliation — Automated Reconciliation](https://github.com/korearn/bank-reconciliation)
**Automated bank-to-internal records reconciliation with Bash orchestration**
`Python` `Pandas` `Bash` `Cron` `WSL` `Rich`
- Detects 3 types of discrepancies: amount mismatches, missing bank records, missing internal records
- Bash script with pre-flight checks, logging and exit codes
- Configurable as a daily cron job for fully automated execution

### ✅ [Exchange Rate Microservice](https://github.com/korearn/exchange-rate-api)
**REST API for real-time currency conversion with caching and fallback**
`Python` `FastAPI` `SQLite` `Pydantic` `Docker` `Uvicorn`
- 5 REST endpoints with automatic Swagger documentation via FastAPI
- SQLite cache with configurable TTL to reduce external API calls
- Automatic fallback rates when Frankfurter API is unavailable
- Dockerfile included for portable containerized deployment

### ✅ [Infra Monitor — Infrastructure Monitor with AI](https://github.com/korearn/infra-monitor)
**Real-time system monitoring daemon with LLM-powered diagnostics**
`Python` `psutil` `Bash` `SQLite` `LMStudio` `Rich`
- Monitors CPU, RAM, disk and network every N seconds (configurable)
- Detects anomalies against configurable thresholds with cooldown pattern
- Generates natural language diagnostics using a local LLM via LMStudio
- Bash scripts for daemon control (start/stop/status) with PID management

### ✅ [ETL Pipeline — Financial & Weather Data](https://github.com/korearn/etl-pipeline)
**Automated ETL pipeline extracting financial and climate data into PostgreSQL**
`Python` `PostgreSQL` `Pandas` `Frankfurter API` `Open-Meteo API` `Bash` `Cron`
- Extracts historical exchange rates and weather data from free public APIs
- Transforms and cross-joins both sources into a unified daily summary table
- Idempotent upsert pattern — safe to run multiple times without duplicates
- Structured logging with timestamps and daily cron job automation

### ✅ [Credit Scoring API](https://github.com/korearn/credit-scoring-api)
**ML-powered credit scoring with AI-generated explanations**
`Python` `FastAPI` `scikit-learn` `SQLite` `LMStudio` `Pydantic`
- Random Forest model trained on 5,000 synthetic profiles to predict default probability
- Converts default probability to 300-850 credit score scale with risk categorization
- Local LLM generates personalized natural language explanations for each decision
- Full audit trail in SQLite — every scoring decision logged for regulatory compliance

### ✅ [Financial RAG Assistant](https://github.com/korearn/financial-rag)
**Document Q&A system using RAG with local embeddings and LLM**
`Python` `FastAPI` `ChromaDB` `sentence-transformers` `LMStudio` `pypdf`
- Indexes financial PDF documents into ChromaDB as semantic vector embeddings
- Retrieves relevant fragments by semantic similarity, not keyword matching
- Generates answers using a local LLM grounded exclusively in your documents
- Supports multilingual queries — automatically detects question language

---

## 🚀 Other Projects

### [🐍 Python Zero to Hero](https://github.com/korearn/python-zero-to-hero)
**Structured journey to Python mastery**
`Python 3` `Algorithms` `Data Structures` `OOP`
- Core concepts implemented with Pareto Principle approach
- Real-world mini-projects and logic exercises

### [SRE Learning Path](https://github.com/korearn/sre-learning-path)
**Production-ready log analyzer with full DevOps pipeline**
`Python` `Flask` `Kubernetes` `Docker` `Terraform`
- Containerized application with health checks and auto-scaling
- Infrastructure as Code integration

### [SQL Database Practice](https://github.com/korearn/sql-practice)
**Database management and query optimization**
`SQL` `SQLite` `Database Design`
- Complex queries, schema normalization, and performance tuning

---

## 🛠️ Technical Stack

### 💻 Backend & Programming
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" height="40" alt="flask" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="40" alt="fastapi" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" height="40" alt="sqlite" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="40" alt="bash" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" height="40" alt="go" />
</div>

### 🤖 AI & Data
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="40" alt="pandas" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="40" alt="numpy" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" height="40" alt="sklearn" />
</div>

### 🔧 Cloud & Infrastructure
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="docker" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="40" alt="kubernetes" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" height="40" alt="terraform" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="linux" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" height="40" alt="aws" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git" />
</div>

---

## 📈 Current Focus

- **Fintech Portfolio** — building a series of 8 production-inspired banking and AI projects
- **Local AI Integration** — connecting LLMs (Qwen, Gemma, Deepseek) to real backend systems via LMStudio
- **Backend Architecture** — REST APIs, microservices, and data pipelines with Python
- **DevOps Automation** — Bash scripting, cron jobs, and Linux system automation

---

## 📊 GitHub Activity
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/korearn/leonardoleon/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/korearn/leonardoleon/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/korearn/leonardoleon/output/github-snake.svg" />
</picture>

<br clear="both">

---

## 📫 Let's Connect
<div align="left">
  <a href="https://www.linkedin.com/in/leonardoleonh/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin" />
  </a>
  <a href="mailto:leo.dleon55@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail" />
  </a>
</div>

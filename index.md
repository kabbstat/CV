---
layout: default
title: Mohamed Kabbaj - Resume
lang: en
permalink: /
---

<div class="lang-switch">
  <a href="./" class="lang-btn active">🇬🇧 English</a>
  <a href="./fr" class="lang-btn">🇫🇷 Français</a>
</div>

# Mohamed Kabbaj

**Data Scientist & MLOps Engineer | MS at Télécom Paris**  
📍 Paris, France

[![Email](https://img.shields.io/badge/Email-mohamed.kabbaj%40telecom--paris.fr-blue?style=flat&logo=gmail)](mailto:mohamed.kabbaj@telecom-paris.fr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed_Kabbaj-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/mohamed-kabbaj-mlops251b7273153/)
[![GitHub](https://img.shields.io/badge/GitHub-kabbstat-181717?style=flat&logo=github)](https://github.com/kabbstat)

---

## 👨‍💻 Profile

Statistical Engineer with **6 years of experience**, currently specializing in **AI & MLOps at Télécom Paris**. I design and deploy **scalable, reproducible, and monitored** machine learning systems, from experimentation to production. My recent work focuses on operationalizing **Large Language Models (LLMOps)**, advanced explainability, and high-performance distributed architectures.

---

## 💼 Professional Experience & Projects

### 🤖 **Gen AI LLMOps** _(Oct. 2025 - Present)_
> **Covéa**, Paris — Capstone Project – Télécom Paris Master's

Automated classification of "Legal Protection" claims (8,566 claims, 83 GMF/MAAF/MMA/Natixis contracts).

- **Fine-tuning & Graph RAG**: Knowledge Graph (**NetworkX**, 2,083 nodes) + legal embeddings (**Solon/ChromaDB**). Fine-tuning **Mistral-7B** (**LoRA/SFT**), reinforcement alignment (**DPO, PPO, GRPO**). 76% accuracy (vs 60% baseline)
- **Hybrid Pipeline**: Semantic search → **BFS** graph navigation → structured legal context → LLM reasoning. Entity extraction via **Qwen2.5-72B**. Multi-GPU deployment (**SLURM**)
- **Data Engineering & Prod**: Ingestion of 83 documents (PDF/DOCX), parsing (**Docling**), intelligent chunking, deduplication. Deployment (**Docker**, **Kubernetes**), **FastAPI** API, CI/CD, monitoring (**MLflow**)

---

### 📊 **Agentic Data Engineer** _(Jan. 2026 - Present)_
> **InvestorSight**, Paris — Freelance

ELT pipeline & multi-agent orchestration for automated analysis of financial documents (SEC Filings, news).

- **Ingestion Pipeline**: ELT architecture on **GCP** — financial data collection (**EDGAR, GDELT API**, scraping), storage on **GCS** (landing zone, hash-based naming) and async messaging via **Cloud Pub/Sub**
- **NLP & Embeddings**: Financial PDF parsing with **Docling Workers**, ACU (Atomic Content Units) extraction, embeddings (**FinLang**) and indexing in a **Vector/Graph DB** for semantic novelty analysis (**NOVASCORE**)
- **Orchestration & Agents**: Scalable deployment on **GKE** (**KEDA** autoscaler), autonomous agents (**Guardian**: Schema Drift & Data Quality; **Analyst**: signal automation), metadata in **PostgreSQL** (JSONB)

---

### 🎯 **Job Recommendation (ML & Collaborative Filtering)** _(Nov 2025)_
> Challenge Data ENS

- **Advanced Algorithms**: Design of a hybrid recommendation system (Collaborative Filtering) and hyperparameter optimization to maximize precision on sparse data

---

### 🗄️ **Big Data Infrastructure & Distributed Processing (Hadoop)** _(Sep 2025)_
> Télécom Paris

Deployment of a 5-node cluster to process a real-world **16 GB dataset (71M rows)**.

- **Data Engineering**: Complete stack configuration (HDFS, YARN, Zookeeper, HBase) and implementation of optimized analysis pipelines via MapReduce Streaming and PySpark

---

### ⚽ **[ELT Football Statistics Pipeline](https://github.com/kabbstat/ELT_FOOTBALL_STAT)** _(Dec 2025)_
> Télécom Paris

Production-grade ELT pipeline for European football statistics analysis (Premier League, La Liga, Ligue 1).

- **Architecture**: Medallion data architecture (Bronze → Silver → Gold) with **PostgreSQL**, ensuring clean separation between raw, cleaned, and aggregated data layers
- **Orchestration & Quality**: Automated weekly extraction via **Apache Airflow**, transformations with **dbt-core**, and 9 automated data quality tests (uniqueness, not-null, custom validations)
- **Visualization & Search**: Interactive **Streamlit** dashboard (5 analytical views) and **Elasticsearch** indexing for advanced querying
- **Containerization**: Fully containerized with **Docker Compose** for reproducible deployment

---

### 🏦 **ML Engineer – Scoring & Fraud Detection (2 years)** _(2023 - Aug 2025)_
> **CIH Bank**, Morocco

Credit scoring & transactional fraud: design, development, production deployment and management.

- **Banking Scorecard**: Scoring grid (**WoE, IV, Logit Lasso**), Gini maximization, deployed in production
- **Fraud Detection**: **XGBoost** + resampling (**SMOTE**) on imbalanced data, recall/false positives optimization
- **MLOps**: CI/CD pipelines, drift monitoring (**Data Drift, PSI**), regulatory compliance
- **Management**: Scoping with Risk & Compliance teams, performance reporting and business impact

---

### 📊 **Data Engineer & Statistical Engineer (4 years)** _(2019 - Aug 2023)_
> **Ministry of Higher Education**, Rabat

Leading data strategy and statistical modeling for public policies.

- **Data Cleaning**: Cleaning, structuring and ensuring reliability of university data
- **Modeling**: Design of demographic projection models (Age-Period-Cohort)
- **Dashboarding**: Design and automation of KPI dashboards for national higher education governance

---

### 🌾 **Data Scientist Consultant (Freelance)** - Agro-Climatic Project _(Mar - Jun 2023)_
> Morocco

- **Modeling**: Kalman Filters to estimate price volatility facing climate shocks
- **Tech**: Satellite image analysis (NDVI) and spatial data processing pipelines

---

### 📈 **Data Scientist Intern (Research)** _(2019 - 6 months)_
> **Ministry of Economy**, Rabat

- **Topic**: Economic Complexity and Regional Specialization
- **Publication**: Poster at Utrecht University "Economic Complexity workshop"

---

## 🛠️ Technical Skills

### Operations & MLOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_(GKE)-326CE5?style=flat&logo=kubernetes&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)

`CI/CD` `dbt` `DVC` `KubeFlow` `FastAPI` `Monitoring` `Model Drift` `Terraform` `SLURM`

### GenAI & NLP
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

`LLMs (Fine-tuning, RAG)` `Transformers` `Deep Learning` `NLP` `Embeddings` `Computer Vision` `CNN` `ViT` `GNN` `GAN` `VAE` `RL:PPO/GRPO` `Transfer Learning`

### Big Data
![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)

`HDFS` `DataLake` `MapReduce` `SQL` `Snowflake` `NoSQL (Neo4j, MongoDB)` `NetworkX` `ElasticSearch`

### ML & Statistics
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)

`Supervised/Unsupervised Learning` `ML with Graphs` `Bayesian Inference` `Spatial Econometrics` `Time Series`

---

## 🎓 Education

### 📜 **Databricks Certified Data Engineer Associate** _(2025)_
📍 **Databricks**

### **Advanced Master in AI & MLOps** _(2024 - 2026)_
📍 **Télécom Paris**, Paris  
Focus: LLMs, MLOps, Distributed Systems

### **State Engineer in Statistics & Applied Economics** _(2016 - 2019)_
📍 **INSEA**, Rabat

### **Preparatory Classes for Grandes Écoles (CPGE)** _(2014 - 2016)_
📍 MPSI/MP - Mathematics & Physics

---

## 🌍 Languages

| Language | Level |
|----------|-------|
| 🇫🇷 French | Fluent |
| 🇬🇧 English | Professional |
| 🇲🇦 Arabic | Native |

---

## 📫 Contact

📧 **Email:** [mohamed.kabbaj@telecom-paris.fr](mailto:mohamed.kabbaj@telecom-paris.fr)  
📱 **Phone:** +33 7 45 68 25 86  
💼 **LinkedIn:** [Mohamed Kabbaj](https://www.linkedin.com/in/mohamed-kabbaj-mlops251b7273153/)  
🐙 **GitHub:** [kabbstat](https://github.com/kabbstat)

---

<p align="center">
  <b>Open to opportunities in Data Science, MLOps & AI</b><br>
  <i>Available for end-of-studies internship or freelance missions</i>
</p>

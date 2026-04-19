# Mohamed Kabbaj

**Data Scientist & MLOps | MS à Télécom Paris**  
📍 Paris, France

[![Email](https://img.shields.io/badge/Email-mohamed.kabbaj%40telecom--paris.fr-blue?style=flat&logo=gmail)](mailto:mohamed.kabbaj@telecom-paris.fr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed_Kabbaj-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/mohamed-kabbaj-mlops251b7273153/)
[![GitHub](https://img.shields.io/badge/GitHub-kabbstat-181717?style=flat&logo=github)](https://github.com/kabbstat)

---

## 👨‍💻 Profil

Ingénieur statisticien avec **6 ans d'expérience**, actuellement spécialisé en **IA & MLOps à Télécom Paris**. Je conçois et déploie des systèmes d'apprentissage automatique **scalables, reproductibles et monitorés**, depuis la phase d'expérimentation jusqu'à la mise en production. Mes travaux récents portent sur l'opérationnalisation de **Large Language Models (LLMOps)**, l'explicabilité avancée et les architectures distribuées haute-performance.

---

## 💼 Expériences Professionnelles & Projets

### 🤖 **IA Gen LLMOps — CDD 12 mois** _(Juil. 2025 - En cours)_
> **Covéa**, Paris

Conception d'un système multi-agents pour l'analyse automatisée de contrats d'assurance.

- **Data Engineering** : Pipeline d'ingestion intégrant le parsing de mise en page (**Docling**) et la réconciliation de métadonnées hétérogènes (**Fuzzy Logic & SQL**)
- **Fine-tuning & Graph RAG** : Adaptation de **Mistral 7B** (**LoRA**) et fusion d'un **Knowledge Graph (Neo4j)** avec un **Vector Store (Chroma)** via **LangChain**
- **Orchestration Multi-Agents** : Architecture d'agents collaboratifs avec raisonnement **Chain-of-Thought (CoT)** pour la décomposition et l'analyse de documents juridiques longs via **LangGraph**
- **Mise en Production** : Déploiement conteneurisé (**Docker**, **Kubernetes**), API de serving via **FastAPI**, pipeline CI/CD et monitoring des performances modèles (**MLflow**, drift detection), observabilité des pipelines RAG et suivi des métriques LLM (latence, qualité des réponses)

---

### 📊 **Agentic Data Engineer** _(Jan. 2026 - En cours)_
> **InvestorSight**, Paris — Freelance

Pipeline ELT & orchestration multi-agents pour l'analyse automatisée de documents financiers (SEC Filings, news).

- **Pipeline d'Ingestion** : Architecture ELT sur **GCP** — collecte de données financières (**EDGAR, GDELT API**, scraping), stockage sur **GCS** (landing zone, nommage par hashage) et messaging asynchrone via **Cloud Pub/Sub**
- **NLP & Embeddings** : Parsing de PDF financiers avec **Docling Workers**, extraction d'ACU (Atomic Content Units), embeddings (**FinLang**) et indexation dans une **Vector/Graph DB** pour l'analyse sémantique de nouveauté (**NOVASCORE**)
- **Orchestration & Agents** : Déploiement scalable sur **GKE** (**KEDA** autoscaler), agents autonomes (**Guardian** : Schema Drift & Data Quality ; **Analyst** : signal automation), métadonnées dans **PostgreSQL** (JSONB)

---

### 🎯 **Recommandation d'Emploi (ML & Collaborative Filtering)** _(Nov 2025)_
> Challenge Data ENS

- **Algorithmique Avancée** : Conception d'un système de recommandation hybride (Filtrage Collaboratif) et optimisation des hyperparamètres pour maximiser la précision sur des données éparses

---

### 🗄️ **Infrastructure Big Data & Traitement Distribué (Hadoop)** _(Sep 2025)_
> Télécom Paris

Déploiement d'un cluster sur 5 nœuds pour traiter un dataset réel de **16 Go (71M lignes)**.

- **Data Engineering** : Configuration complète de la stack (HDFS, YARN, Zookeeper, HBase) et implémentation de pipelines d'analyse optimisés via MapReduce Streaming et PySpark

---

### ⚽ **[Pipeline ELT Football Statistics](https://github.com/kabbstat/ELT_FOOTBALL_STAT)** _(Déc 2025)_
> Télécom Paris

Pipeline ELT de niveau production pour l'analyse de statistiques du football européen (Premier League, La Liga, Ligue 1).

- **Architecture** : Architecture de données Medallion (Bronze → Silver → Gold) avec **PostgreSQL**, assurant une séparation nette entre données brutes, nettoyées et agrégées
- **Orchestration & Qualité** : Extraction hebdomadaire automatisée via **Apache Airflow**, transformations avec **dbt-core**, et 9 tests automatisés de qualité des données (unicité, non-nullité, validations custom)
- **Visualisation & Recherche** : Dashboard interactif **Streamlit** (5 vues analytiques) et indexation **Elasticsearch** pour des requêtes avancées
- **Conteneurisation** : Entièrement conteneurisé avec **Docker Compose** pour un déploiement reproductible

---

### 📊 **Data Engineer & Ingénieur Statisticien (5 ans)** _(2019 - Août 2024)_
> **Ministère de l'Enseignement Supérieur**, Rabat

Pilotage de la stratégie data et modélisation statistique pour les politiques publiques.

- **Data Cleaning** : Nettoyage, structuration et fiabilisation des données des universités pour les rendre exploitables
- **Modélisation** : Conception de modèles de projection démographique (Âge-Période-Cohorte)
- **Dashboarding** : Conception et automatisation de dashboards KPI pour le pilotage national de l'enseignement supérieur

---

### 🌾 **Consultant Data Scientist (Freelance)** - Projet Agro-Climatique _(Mar - Jun 2023)_
> Maroc

- **Modélisation** : Filtres de Kalman pour estimer la volatilité des prix face aux chocs climatiques
- **Tech** : Analyse d'images satellites (NDVI) et pipelines de traitement de données spatiales

---

### 📈 **Stagiaire Data Scientist (Recherche)** _(2019 - 6 mois)_
> **Ministère de l'Économie**, Rabat

- **Sujet** : Complexité Économique et Spécialisation Régionale
- **Publication** : Poster à l'université d'Utrecht "Economic Complexity workshop"

---

## 🛠️ Compétences Techniques

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

`Apprentissage Supervisé/Non-supervisé` `ML with Graphes` `Inférence Bayésienne` `Économétrie Spatiale` `Séries Temporelles`

---

## 🎓 Formation

### 📜 **Databricks Certified Data Engineer Associate** _(2025)_
📍 **Databricks**

### **Mastère Spécialisé IA & MLOps** _(2025 - 2026)_
📍 **Télécom Paris**, Paris  
Focus : LLMs, MLOps, Systèmes Distribués

### **Ingénieur d'État en Statistique & Économie Appliquée** _(2016 - 2019)_
📍 **INSEA**, Rabat

### **Classes Préparatoires aux Grandes Écoles (CPGE)** _(2014 - 2016)_
📍 MPSI/MP - Mathématiques & Physique

---

## 🌍 Langues

| Langue | Niveau |
|--------|--------|
| 🇫🇷 Français | Courant |
| 🇬🇧 Anglais | Professionnel |
| 🇲🇦 Arabe | Natif |

---

## 📫 Contact

📧 **Email:** [mohamed.kabbaj@telecom-paris.fr](mailto:mohamed.kabbaj@telecom-paris.fr)  
📱 **Téléphone:** +33 7 45 68 25 86  
💼 **LinkedIn:** [Mohamed Kabbaj](https://www.linkedin.com/in/mohamed-kabbaj-mlops251b7273153/)  
🐙 **GitHub:** [kabbstat](https://github.com/kabbstat)

---

<p align="center">
  <b>Ouvert aux opportunités en Data Science, MLOps & IA</b><br>
  <i>Disponible pour un stage de fin d'études ou des missions freelance</i>
</p>

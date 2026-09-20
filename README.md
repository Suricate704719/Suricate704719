# Loÿs Chataigner | Data Engineer & MLOps 🚀

Ingénieur Data spécialisé dans la conception d'architectures de données robustes, le déploiement de modèles de Machine Learning (MLOps) et l'orchestration de pipelines cloud-native. J'interviens sur l'ensemble de la chaîne de valeur de la donnée : de l'ingestion brute (ELT) au déploiement d'architectures d'Intelligence Artificielle Générative (RAG).

📫 **Me contacter :** loyschataigner@gmail.com

## 🛠 Stack Technique

* **Data Engineering & ETL/ELT :** Python (Pandas, NumPy), dbt (Data Build Tool), Airbyte, PySpark.
* **Databases & Modélisation :** PostgreSQL (SCD Type 2, Triggers), MongoDB, Cassandra, SQLite.
* **MLOps & Déploiement :** Docker, BentoML, Pydantic, FastAPI.
* **Orchestration & Streaming :** Kestra, Apache Airflow, Apache Kafka.
* **Cloud & Architecture :** AWS (S3, ECS, DocumentDB), Google Cloud Run (GCP).
* **IA & NLP :** LangChain, Modèles LLM (Mistral, OpenAI), Bases vectorielles, architecture RAG.
* **Qualité & CI/CD :** Pytest, Tests unitaires et d'intégration, DevSecOps.

---

## 📂 Featured Use Cases (Portfolio)

### 1. [Modern-Data-Stack-AWS](lien-vers-repo-1)
**Architecture ELT, Streaming temps réel et Orchestration**
* **Contexte :** Modernisation de la chaîne de valeur de la donnée d'une approche ETL classique vers un pipeline ELT hybride.
* **Architecture :** Ingestion via **Airbyte**, modélisation analytique versionnée et testée avec **dbt**. Intégration de clusters **Apache Kafka** pour le traitement asynchrone des événements critiques.
* **Opérations :** Modélisation d'une infrastructure cloud **AWS** (S3, VPC, IAM) et supervision globale via **Kestra** pour garantir l'idempotence des tâches, l'observabilité de la donnée et la gestion automatisée des alertes.

### 2. [MLOps-GenAI-Ecosystem](lien-vers-repo-2)
**Déploiement d'API Prédictives (Random Forest) et Génératives (RAG)**
* **MLOps Prédictif :** Prédiction de la consommation énergétique de bâtiments (Seattle). Optimisation algorithmique via `GridSearchCV`, encapsulation du modèle via **BentoML** et **Pydantic** pour un typage strict des requêtes, et déploiement serverless sur **Google Cloud Run**.
* **IA Générative :** Conception d'un système conversationnel interne basé sur la technique du **RAG** (Retrieval-Augmented Generation). Vectorisation de corpus documentaires, indexation en base vectorielle, et orchestration via **LangChain** et les LLMs (Mistral/OpenAI) pour fournir des réponses sourcées et fiables.

### 3. [NoSQL-Secured-Migration](lien-vers-repo-3)
**Ingénierie Big Data, Sécurité et automatisation de tests**
* **Contexte :** Migration conteneurisée des données médicales d'un hôpital vers une architecture NoSQL distribuée.
* **Technique :** Développement d'un pipeline Python d'injection en lots sous **MongoDB**. Application stricte du *DevSecOps* : création automatisée de rôles restreints via scripts d'initialisation, protection des identifiants (variables d'environnement).
* **Qualité :** Orchestration via **Docker Compose** et mise en place d'une suite de tests automatisés avec **Pytest** garantissant la conformité des données avant/après migration (réconciliation à 100%).

### 4. [SQL-Architecture-Audit](lien-vers-repo-4)
**Modélisation relationnelle, Audit d'intégrité et SCD Type 2**
* **Conception :** Création d'un modèle en étoile normalisé pour un data warehouse immobilier, permettant des requêtes analytiques avancées (fonctions de fenêtrage `RANK() OVER`) sur le dynamisme économique national.
* **Sécurité & Audit :** Investigation d'une anomalie financière via analyse de logs. Refonte de l'architecture pour intégrer une historisation **Slowly Changing Dimension (SCD) Type 2**. Protection transactionnelle native sous **PostgreSQL** via clés étrangères strictes, contraintes `CHECK` et déclencheurs `BEFORE UPDATE TRIGGER`.

### 5. [Global-Education-Analytics](lien-vers-repo-5)
**Analyse stratégique à grande échelle et Data Quality**
* **Contexte :** Stratégie d'expansion internationale EdTech basée sur la base de données massive EdStats de la Banque Mondiale (880 000+ lignes).
* **Analyse :** Data cleaning complexe (imputation régionale), filtrage sémantique automatisé via Regex, et Feature Engineering. Détection des redondances statistiques via matrice de corrélation de Spearman et visualisations Seaborn.
* **Impact :** Création d'un algorithme de scoring multicritère pondéré et livraison de recommandations d'implantation ciblées (Business Intelligence).

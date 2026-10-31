# Mohamed Amine Tarik

**Data Science student at ENSIAS** (Business Intelligence & Analytics engineering degree, Casablanca).
I build machine learning and LLM systems end to end, from data preparation to evaluation and
deployment, and the data pipelines that feed them.

🎯 Looking for a **final-year internship (PFE) in Data Science** (or Data Engineering) from **February 2027**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed_Amine_Tarik-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-amine-tarik)
[![Email](https://img.shields.io/badge/Email-m.amine.tarik%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:m.amine.tarik@gmail.com)

---

## Featured projects

### Data Science & AI

| Project | What I built | Key results |
|---|---|---|
| [**Multilingual recipe RAG**](https://github.com/mtaarik/moroccan-recipe-rag) | RAG assistant in French, English and Moroccan Darija over 235k recipes: hybrid search (BM25 + multilingual embeddings), cross-encoder reranking, LLM query understanding, cited answers, 81-query benchmark and ablations | nDCG@10 **0.42 → 0.83**, answer faithfulness **2.1 → 4.1-4.5 / 5**, correct abstention on **7/7** unanswerable questions |
| [**Credit risk scoring (MLOps)**](https://github.com/mtaarik/credit-risk-scoring-mlops) | Default prediction on 30k clients: model comparison, recall-driven decision threshold, then a FastAPI service tracked with MLflow, containerized with Docker and deployed to AWS EC2 by GitHub Actions | XGBoost catches **80% of defaults** (ROC-AUC 0.78) |
| [**Textual Inversion vs DreamBooth**](https://github.com/mtaarik/textual-inversion-generative-ai) | Team project: teaching Stable Diffusion v1.5 a new object from 10 photos and comparing two personalization methods | 4 KB embedding vs 3.1 MB LoRA, trade-off between size and fidelity |
| [**House prices regression**](https://github.com/mtaarik/House-Prices) | Kaggle competition: feature engineering, Lasso / XGBoost, 5-fold cross-validation, blending | CV RMSLE **0.111** (Lasso) |

### Data Engineering

| Project | What I built | Key results |
|---|---|---|
| [**Plum'Air real-time Lakehouse**](https://github.com/mtaarik/plumair-pipeline-lakehouse) (OCP internship) | Lambda architecture for industrial air-quality monitoring: NiFi → Kafka → Iceberg on MinIO → Trino, dbt Medallion model (3NF Silver, star schema with SCD2 Gold), Airflow, Power BI | 580,800 sensor events, real-time alert path to PostgreSQL, **32 dbt data tests** on every run |
| [**Real-time stock pipeline**](https://github.com/mtaarik/real-time-stocks-mds) | Live Finnhub quotes: Kafka → MinIO → Airflow → Snowflake → dbt (Bronze / Silver / Gold) → Power BI | Fixed a silent data loss beyond 1,000 S3 objects (pagination) |
| [**SQL data warehouse**](https://github.com/mtaarik/sql-data-warehouse-project) | SQL Server warehouse with Bronze / Silver / Gold layers, ETL procedures, star schema and quality checks (course-based) | |

## Experience

- **Data Engineer intern, OCP Group** (Jul. - Aug. 2026): real-time Lakehouse for emissions monitoring (Plum'Air above).
- **Data Scientist intern, ARKEOS Group** (Jun. - Jul. 2025): sales forecasting with XGBoost, integrated into a stock management web app (Flask, React).

## Tech stack

**Data Science & AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow%20%2F%20Keras-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

Machine learning, deep learning, LLM / RAG, information retrieval evaluation, generative AI (Stable Diffusion).

**MLOps & deployment**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

**Data Engineering**

![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache NiFi](https://img.shields.io/badge/Apache_NiFi-728E9B?style=for-the-badge&logo=apache&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=for-the-badge&logo=trino&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache_Iceberg-3D7AB8?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge)

ETL / ELT, streaming, Lakehouse and Medallion architecture, data modeling (3NF, star schema, SCD2), data quality testing.

**Business Intelligence**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

DAX, Power Query, SSAS, SSIS.

## Languages

French  (fluent) . English (fluent) · Arabic (native)

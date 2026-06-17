# Hi, I'm Mahwish 👋

**Data Engineer** with 3.5 years of experience designing and delivering cloud-native data pipelines on AWS/Databricks.  
I build scalable ETL systems, lakehouse architectures, and serverless pipelines — with a focus on performance, cost efficiency, and clean infrastructure-as-code.

- 🚀 Reduced Athena query costs by **60%** via columnar Parquet optimization
- ⚡ Improved ETL performance by **40%** through incremental job bookmarking & partitioning
- ☁️ AWS Certified Solutions Architect — Associate (Nov 2024)
- 🏗️ Strong believer in IaC — Terraform for everything

---

## 🛠️ Tech Stack

**Cloud**
![AWS](https://img.shields.io/badge/AWS-S3%20%7C%20Glue%20%7C%20Lambda%20%7C%20Kinesis%20%7C%20Athena%20%7C%20Redshift%20%7C%20QuickSight-orange?logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?logo=terraform&logoColor=white)

**Data Engineering**
![PySpark](https://img.shields.io/badge/PySpark-3.x-E25A1C?logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-Delta%20Lake-FF3621?logo=databricks&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-v2-3E6D9C)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-Streaming-231F20?logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-Orchestration-017CEE?logo=apacheairflow&logoColor=white)

**Languages & Databases**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Redshift%20%7C%20Athena%20%7C%20MySQL-4169E1)

---

## 🚀 Featured Projects

### 🏔️ [AWS Lakehouse ETL Pipeline](https://github.com/moonanjum26/lakehouse-etl-pipeline)
Production-grade lakehouse pipeline using **PySpark + Apache Iceberg + Redshift Serverless**, fully provisioned with Terraform.

- Incremental ingestion via watermark-based filtering — processes only new data on each run
- SCD-1 MERGE with schema evolution using Apache Iceberg Format v2
- Medallion architecture: Bronze → Silver (Iceberg ACID) → Gold (analytics-ready Parquet)
- Full IaC with Terraform — entire stack provisions in under 5 minutes

`AWS Glue` `PySpark` `Apache Iceberg` `Redshift Serverless` `Terraform` `S3`

---

### ⚡ [AWS Serverless Data Pipeline](https://github.com/moonanjum26/aws-serverless-datapipeline)
Event-driven serverless pipeline for healthcare data analytics — zero servers to manage.

- S3 upload triggers Lambda → Glue ETL → Athena → QuickSight dashboards
- ~40% ETL efficiency gain through incremental Glue job bookmarking + optimized partitioning
- ~60% Athena cost reduction by converting raw CSV to columnar partitioned Parquet
- EventBridge + SNS for real-time job alerts; CloudWatch for end-to-end observability

`Lambda` `AWS Glue` `Athena` `QuickSight` `EventBridge` `SNS` `CloudWatch` `Terraform`

---

## 📜 Certifications

☁️ **AWS Certified Solutions Architect – Associate** | Nov 2024 – Nov 2027

---

## 📫 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mahwish%20Anjum-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/mahwish-anjum-61a84347)

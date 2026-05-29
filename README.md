# Manasseh Amoah

**Data & Decision Systems Builder for D2C Brands** - I help companies turn scattered data into decisions.

Most companies sit on valuable data they cannot use. Not because they lack interest, but because they lack the infrastructure to ask and answer their own business questions. I build that infrastructure.

---

## What I do

I implement end-to-end ELT pipelines for D2C companies and SMBs - using proven tools configured for each client's specific context. The deliverable is a documented, tested system the team can maintain independently.

**The process:**
1. Define the business question that needs answering
2. Identify what data exists and where it lives
3. Build the pipeline that automates the answer
4. Hand over a system that runs without manual intervention

**Stack:** Airbyte · dbt · BigQuery / Snowflake / Redshift · Metabase · Airflow · Terraform · GitHub Actions

---

## Portfolio

### [Olist E-Commerce Analytics Pipeline](https://github.com/ManassehOmexes/olist-analytics-pipeline)

End-to-end ELT pipeline on AWS. 100,000+ raw orders → verified, production-ready dashboard. Built to industry standard.

```
[CSV Files] → [S3 Bronze] → [AWS Glue] → [S3 Silver] → [dbt Core] → [Redshift] → [Power BI]
```

**What it demonstrates:** Medallion Architecture · Volume Anomaly Detection · Bronze + Silver Validation Gates · Secrets Management · Terraform IaC · CI/CD · Disaster Recovery · GDPR compliance · OpenLineage

| Metric | Value |
|---|---|
| dbt models | 17 |
| Automated tests | 49 (all passing) |
| Data quality checks | 49 Great Expectations checks |
| Cloud provider | AWS (eu-central-1) |
| Warehouse | Redshift Serverless |

---

### D2C Attribution Stack *(in progress)*

Attribution pipeline for Shopify-based D2C businesses. Answers the question every D2C founder has: which marketing channel actually drives revenue?

```
[Shopify + Meta Ads + Klaviyo] → [Airbyte] → [BigQuery] → [dbt] → [Metabase]
```

Core models: `fct_attribution` · `fct_customer_ltv` · `fct_marketing_efficiency`

---

## Tech Stack

| Domain | Technologies |
|---|---|
| Cloud | AWS — S3, Glue, Redshift Serverless, IAM, Secrets Manager · GCP — BigQuery |
| Orchestration | Apache Airflow 2.x |
| Ingestion | Airbyte (300+ connectors) |
| Transformation | dbt Core — Staging, Intermediate, Marts |
| IaC | Terraform |
| Data Quality | Great Expectations · dbt Tests · dbt-expectations |
| CI/CD | GitHub Actions |
| Visualization | Power BI · Metabase |
| Language | Python 3.11 · SQL |

[![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)](https://aws.amazon.com)
[![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white)](https://cloud.google.com)
[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://python.org)
[![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)](https://getdbt.com)
[![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=Apache%20Airflow&logoColor=white)](https://airflow.apache.org)
[![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat&logo=terraform&logoColor=white)](https://terraform.io)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)](https://github.com/features/actions)

---

## Background

B.Sc. Business Informatics - the combination of business logic and technical precision.

Working across insurance and e-commerce domains. Direct exposure to the data problems of companies without dedicated data teams.

Principle: I only implement code I fully understand. Accuracy over speed.

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manasseh-amoah-9540b9332/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:manasseh.amoah019@gmail.com)

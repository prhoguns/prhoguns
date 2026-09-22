### Philips Rhoguns

Computer Science student at York University (graduating December 2026), Toronto.
Background in 24/7 security operations; building toward data engineering and security analytics.
CompTIA Security+ · AWS Certified DevOps Engineer – Professional · Microsoft PL-400

**Data engineering and analytics**

| | |
|---|---|
| [toronto-open-data-pipeline](https://github.com/prhoguns/toronto-open-data-pipeline) | ELT for City of Toronto open data: CKAN → PostgreSQL → dbt star schema (11 models, 40 tests) → Airflow, with a retrained delay-probability model served by FastAPI. |
| [azure-toronto-data-platform](https://github.com/prhoguns/azure-toronto-data-platform) | The same pipeline Azure-native: Bicep, Data Factory, ADLS Gen2, Databricks (PySpark/Delta medallion), Synapse serverless. |
| [databricks-credit-risk-mlflow](https://github.com/prhoguns/databricks-credit-risk-mlflow) | Credit-risk model in Spark MLlib with the full MLflow lifecycle: tracking, CV tuning, registry alias, batch scoring. AUC 0.78, KS 0.43. |
| [ttc-realtime-pipeline](https://github.com/prhoguns/ttc-realtime-pipeline) | Streaming: live TTC vehicle positions (GTFS-Realtime) → Redpanda/Kafka → idempotent PostgreSQL sink → live route views. |
| [toronto-crime-sql-analytics](https://github.com/prhoguns/toronto-crime-sql-analytics) | Twenty SQL questions on a decade of police data, a findings write-up, and a [live dashboard](https://prhoguns.github.io/toronto-crime-sql-analytics/). |

**Security analytics and detection engineering**

| | |
|---|---|
| [soc-alert-analytics](https://github.com/prhoguns/soc-alert-analytics) | SIEM alert and triage analytics (rule tuning, SLAs, ATT&CK coverage, attack chains) plus Isolation Forest anomaly detection evaluated against planted incidents. |
| [sigma-detection-pack](https://github.com/prhoguns/sigma-detection-pack) | Eleven Sigma rules converted to SQL, Splunk and Sentinel KQL with pySigma, tested in CI against a corpus with planted positives and near-misses. |

[LinkedIn](https://linkedin.com/in/philips-rhoguns-266748180) · orhogun@gmail.com

# RoamWise: Real-Time Travel Data Pipeline
**A real-time travel data pipeline integrating batch & streaming processing with optimized data storage.**

## Project Overview
- **Batch Processing**: Ingests historical travel data from Kaggle into PostgreSQL.
- **Streaming Processing**: Uses Kafka to process real-time flight & weather API data.
- **Optimized Storage**: Combines PostgreSQL (structured) + MongoDB (unstructured) + Redshift (aggregations).
- **Automated Pipelines**: Apache Airflow schedules ETL workflows.

## Tech Stack
- **Languages**: Python, SQL
- **Databases**: PostgreSQL, MongoDB, Redshift
- **ETL & Data Pipelines**: Apache Airflow, Pandas, AWS Glue
- **Streaming**: Kafka, API Integration
- **Cloud Services**: AWS (S3, Lambda, EC2)

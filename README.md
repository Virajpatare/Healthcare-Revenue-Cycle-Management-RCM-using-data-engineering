# Healthcare-Revenue-Cycle-Management-RCM-using-data-engineering
Azure Data Engineering Project – Healthcare Revenue Cycle Management (RCM)

Designed and implemented an end-to-end Azure Data Engineering solution for Healthcare Revenue Cycle Management (RCM) to track patient billing, insurance claims, payments, and account receivables.

Built scalable ETL pipelines using Azure Data Factory (ADF) to ingest data from multiple heterogeneous sources including Azure SQL Databases (EMR data), CSV flat files (insurance claims), and REST APIs (NPI & ICD codes).

Implemented Medallion Architecture (Landing → Bronze → Silver → Gold) on Azure Data Lake Storage (ADLS) for structured data processing and analytics.

Loaded raw data into Bronze layer in Parquet format using dynamic and parallel ADF pipelines with Lookup and ForEach activities.

Performed data cleaning, transformations, data modeling, and SCD Type-2 handling in Silver layer using Delta tables on Azure Databricks.

Developed fact and dimension tables in Gold layer to support BI reporting, KPIs, and dashboards for Accounts Receivable analysis.

Handled multi-hospital data integration with different schemas by creating separate Azure SQL databases and unified data models.

Integrated API-based ingestion for healthcare reference datasets (NPI & ICD codes).

Implemented configuration-driven pipelines and Azure Key Vault for secure credential management.

Optimized pipelines using parallel execution and prepared data for BI teams and downstream analytics.

Worked with Hive Metastore and planned migration to Unity Catalog for governance and data security.

Tech Stack

Azure Data Factory | Azure Data Lake Storage (ADLS) | Azure SQL DB | Azure Databricks | Delta Lake | Parquet | REST APIs | Healthcare RCM Domain

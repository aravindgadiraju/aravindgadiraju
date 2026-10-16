# Aravind Gadiraju

Data Engineer based in Hyderabad, India.

I build and support data pipelines that move engineering and quality data out of on-premise systems into Azure, and turn it into reporting that business teams use day to day. Most of my work sits across three things: writing the pipelines, keeping the scheduled loads healthy, and building the Power BI models on top of them.

## What I work with

**Languages** — Python, SQL, T-SQL, PySpark

**Azure and cloud** — Azure Databricks, Delta Lake, ADLS Gen2, Unity Catalog

**Data engineering** — ETL and ELT, data pipelines, data modeling, incremental loading, query optimization, stored procedures

**Analytics** — Power BI, DAX, Power Query, semantic modeling, star schema, row-level security, incremental refresh

**Tools** — Microsoft SQL Server, Apache Trino, Git, GitLab, Jupyter , Azure Devops

**Working knowledge** — Azure Data Factory, Azure Key Vault

## Featured project

**ALM Azure Data Engineering Platform**

https://github.com/aravindgadiraju/alm-azure-data-engineering

An end-to-end platform that pulls Application Lifecycle Management data out of an on-premise document store and lands it as governed, reportable tables on Azure.

Source → Trino → Azure Data Factory → ADLS Gen2 → Databricks and PySpark → Delta Lake Bronze, Silver and Gold → Azure SQL → Power BI

The repository covers the architecture and the reasoning behind each decision: watermark-based incremental loading, one metadata-driven ADF pipeline instead of six copies, a data quality gate that stops a bad run before anything is published, and an atomic swap on the serving layer so users never see a half-loaded table.

## Currently

Deepening my Azure data engineering work and learning Snowflake.

## Reach me

LinkedIn — https://www.linkedin.com/in/aravind-gadiraju-aa25b31a4

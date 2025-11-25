# Designing-a-Lakehouse-platform-using-Medallion-Architecture-pattern
Design and Implementation of a Medallion-Based Lakehouse Platform Using Databricks and ADLS


Designed a scalable Lakehouse architecture using the Medallion pattern (Bronze, Silver, Gold) with Databricks and Azure Data Lake Storage. Data was ingested from Kafka topics and SQL databases into an ADLS landing zone using Autoloader-based streaming pipelines. Built 3 Bronze tables as raw, source-of-truth datasets; 8 Silver tables for cleansing, deduplication, enrichments, and dataset joins; and 2 Gold tables optimized for downstream analytics. End-to-end processing was orchestrated through Databricks notebooks with fully streaming pipelines.
<img width="1920" height="1080" alt="Screenshot (172)" src="https://github.com/user-attachments/assets/6de60401-6b5d-489f-b0ef-a554352ad7ac" />

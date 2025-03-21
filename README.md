# Azure-data-engineering-project-

 

- Designed and implemented a Medallion Architecture (Landing → Bronze → Silver → Gold) data pipeline for Healthcare Revenue Cycle Management (RCM) using Azure Data Factory (ADF), Azure Databricks, Delta Lake, and ADLS Gen2.  
- Ingested EMR (Azure SQL DB), Claims (Flat Files), NPI & ICD Codes (Public API) into Azure Data Lake Storage (ADLS Gen2), storing raw data in Parquet format in the Bronze layer.  
- Processed and transformed data in Databricks, implementing data cleaning, SCD Type 2 (Slowly Changing Dimensions), and Common Data Model (CDM) in the Silver layer using Delta Tables.  
- Created Fact and Dimension tables in the Gold layer, optimizing data for business intelligence and analytics teams for KPIs like Days in AR, AR > 90 Days, and Claims Processing Efficiency.  
- Implemented audit logging and incremental data ingestion in ADF, utilizing Key Vault for secure credential management and metadata-driven pipelines for scalable data ingestion.  
- Optimized ADF pipelines from sequential to parallel execution, reducing data processing time and enhancing system scalability.  
- Developed a Unity Catalog for centralized metadata management in Databricks, enhancing data governance and access control.  
- Applied best practices for Azure Data Engineering, including naming conventions, pipeline retries, is_active flag implementation, and structured folder hierarchy in ADLS Gen2.  





# Nyc-Taxi-Azure-Data-Engineering-Project
🚀 Project Highlights:
Data Ingestion via APIs: Configured pipelines in Azure Data Factory to dynamically fetch data from APIs and load it into the Bronze Layer in Azure Data Lake Storage.
Data Cleaning & Transformation: Utilized PySpark in Databricks to clean and validate the data. Transformed data was then moved to the Silver Layer.
Delta Lake Integration: Created Delta Lake to implement time travel and versioning features for consistent data management. Final datasets were loaded into the Gold Layer for advanced analytics.
Power BI Reporting: Integrated Power BI with the Gold Layer, enabling the delivery of meaningful insights through interactive dashboards.
🔑 Challenges We Tackled:
API Data Handling: Managed the complexity of ingesting large-scale, dynamic data from APIs.
Data Pipeline Dynamics: Built a dynamic pipeline to ensure monthly data processing with minimal manual intervention.
Data Lake Layering: Implemented a structured approach with Bronze, Silver, and Gold layers, streamlining data flow.
Error Recovery: Designed robust mechanisms for error handling to maintain the continuity of data pipelines.
🌱 New Learnings:
Dynamic Pipelines: Learned to create adaptive workflows in Azure Data Factory using If Condition Activity and metadata-driven processing.
Delta Lake Features: Mastered advanced Delta Lake capabilities like data versioning and time travel for historical querying and rollback.
Integration Best Practices: Gained experience in seamlessly connecting data lakes with Power BI for effective reporting.

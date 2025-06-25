# 🎬 Netflix Data Warehouse Pipeline using Snowflake, dbt & BI Tools

This project demonstrates an end-to-end modern data pipeline to transform Netflix CSV data into analytics-ready tables using **Amazon S3**, **Snowflake**, and **dbt**, with visualizations powered by **Power BI**, **Looker Studio**, and **Tableau**. It follows a layered architecture with raw, staging, and serving layers to ensure clean, testable, and modular data transformations.

<img width="907" alt="Architecture" src="https://github.com/user-attachments/assets/dd9cf6c9-97db-4b1b-a8cd-c74d3464c8fd" />



## 🔧 Tech Stack
- **Amazon S3** for raw data storage  
- **Snowflake** as the cloud data warehouse  
- **dbt (Data Build Tool)** for transformation, testing, and orchestration  
- **Power BI**, **Looker Studio**, **Tableau** for business intelligence and reporting  
- **CSV** as the initial input format



## ⚙️ How It Works
- Netflix data in **CSV format** is extracted and loaded into **Amazon S3**.
- Data is ingested from S3 into **Snowflake's raw layer**.
- **dbt** transforms the data across layers:
  - Raw → Staging → Serving (Dev)
  - Enables testing, modularization, and documentation of models.
- Transformed data in the serving layer is visualized using **Power BI**, **Looker Studio**, and **Tableau** for business insights.



## 📌 Key Highlights
- Designed a **modular ELT pipeline** using Snowflake and dbt with layered architecture.
- Implemented **data transformation, testing, and orchestration** using dbt best practices.
- Enabled **interactive dashboards** in Power BI, Tableau, and Looker Studio from the final serving layer.
- Demonstrated a **scalable and maintainable data warehouse model** for analytical use cases.





# 📊 Adventure Works Data Engineering Project

This project demonstrates a complete end-to-end **data engineering pipeline** using **Azure Databricks**, **Azure Data Lake Storage (ADLS)**, **Azure Synapse Analytics**, and **Power BI**. It follows the Medallion Architecture pattern: **Bronze → Silver → Gold**, and delivers meaningful business insights through data visualization.

---

## 🛠️ Tech Stack

- **Cloud Platform**: Microsoft Azure  
- **Processing**: Azure Databricks (Apache Spark with PySpark)  
- **Storage**: Azure Data Lake Storage Gen2 (ADLS)  
- **Analytics Layer**: Azure Synapse Analytics  
- **Visualization**: Power BI  
- **Languages Used**: PySpark, SQL  

---

## 🎯 Project Goals

- Build a scalable data pipeline using Databricks and Delta Lake.
- Clean and transform raw data into structured layers.
- Serve data to Azure Synapse for enterprise querying.
- Build interactive dashboards using Power BI.

---

## 📚 Topics I Covered

- 💡 Introduction to Azure Data Architecture  
- 🆓 Setting up an Azure Free Account  
- 🔍 Exploring Data via APIs (Data Understanding)  
- ⚙️ Data Ingestion (Bronze Layer)  
- ☁️ Creating Azure Resources  
- 🛠️ Azure Data Factory (ADF) Overview & Real-Time Scenarios  
- 📂 Azure Data Lake Gen2 Overview  
- 🔄 ETL Pipelines with Azure Data Factory  
- 🧠 Azure Databricks Setup & Cluster Configuration  
- 🛡️ Working with Service Principals  
- 🧪 Data Transformation using PySpark & Databricks (Silver Layer)  
- 🔥 Apache Spark Concepts  
- 📊 Big Data Analytics with PySpark  
- 🧱 Azure Synapse Analytics (Gold Layer)  
- 🧩 Using `OPENROWSET()` & External Tables in Synapse  
- 🔗 Integrating Synapse Data Warehouse with Power BI  
- 🧭 Azure Data Engineer Interview Questions & Best Practices


## ✅ Workflow Overview

The project follows a structured **Medallion Architecture** that moves data through three key transformation layers and then serves it for analysis:

### 1️⃣ Bronze Layer – Raw Data Ingestion  
Raw data is ingested from external sources and stored in its original form in the Bronze layer. This acts as the single source of truth and enables traceability.

### 2️⃣ Silver Layer – Data Cleaning and Transformation  
The ingested data is cleaned, transformed, and enriched in the Silver layer. This includes tasks like parsing dates, filtering nulls, and generating new columns such as `Year` and `Month`.

### 3️⃣ Gold Layer – Business-Level Aggregation  
Data is aggregated in the Gold layer to create business-ready tables that summarize key metrics. This layer supports reporting, analytics, and machine learning workflows.

### 4️⃣ Data Serving via Azure Synapse  
The refined Gold layer data is made queryable through Azure Synapse Analytics, enabling SQL-based access, enterprise-wide sharing, and integration with BI tools.

### 5️⃣ Visualization with Power BI  
Final dashboards are created in Power BI to visualize KPIs, revenue trends, and performance breakdowns across dimensions like region, month, and product.

## 📷 Screenshot Gallery

Below are some screenshots representing some steps of the project:

![Photo1](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo1.png)
![Photo2](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo2.png)
![Photo3](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo3.png)
![Photo4](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo4.png)
![Photo5](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo5.png)
![Photo6](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo6.png)
![Photo7](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo7.png)
![Photo8](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo8.png)
![Photo9](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo9.png)
![Photo10](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo10.png)
![Photo11](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo11.png)
![Photo12](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo12.png)
![Photo13](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo13.png)
![Photo14](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo14.png)
![Photo15](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo15.png)
![Photo16](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo16.png)
![Photo17](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo17.png)
![Photo18](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo18.png)
![Photo19](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo19.png)
![Photo20](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo20.png)
![Photo21](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo21.png)
![Photo22](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo22.png)
![Photo23](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo23.png)
![Photo24](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo24.png)
![Photo25](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo25.png)
![Photo26](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo26.png)
![Photo27](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo27.png)
![Photo28](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo28.png)
![Photo29](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo29.png)
![Photo30](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo30.png)
![Photo31](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo31.png)
![Photo32](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo32.png)
![Photo33](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo33.png)
![Photo34](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo34.png)
![Photo35](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo35.png)
![Photo36](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo36.png)
![Photo37](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo37.png)
![Photo38](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo38.png)
![Photo39](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo39.png)
![Photo40](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo40.png)
![Photo41](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo41.png)
![Photo42](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo42.png)
![Photo43](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo43.png)
![Photo44](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo44.png)
![Photo45](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo45.png)
![Photo46](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo46.png)
![Photo47](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo47.png)
![Photo48](https://github.com/neha-dev-dot/Adventure-Works-Data-Engineering-Project/blob/main/Images/Photo48.png)


## 🧠 Learning Outcomes
- Designing and building scalable data pipelines using Azure Data Factory  
- Performing transformations using Databricks + PySpark  
- Leveraging Azure Synapse for analytics and warehousing  
- Handling real-time data and large-scale processing with Apache Spark  

---

## ✅ Final Summary

This project demonstrates a complete real-world implementation of a modern **Data Lakehouse Architecture** using Azure tools. From ingesting raw data into the Bronze layer, transforming and enriching it in the Silver layer, to serving analytics-ready data in the Gold layer and visualizing it through Power BI — this pipeline showcases the full lifecycle of data engineering.

> It not only reflects a solid understanding of **Azure Databricks**, **Delta Lake**, and **Synapse Analytics**, but also emphasizes performance optimization, modular pipeline design, and enterprise readiness.

---

## 🙌 Acknowledgments

I would like to thank:
- The **Microsoft Azure documentation** and community for guidance and best practices.
- My mentors and peers who supported me throughout this learning journey.
- The **AdventureWorks dataset** for providing a rich foundation for data engineering exploration.

---

## 📬 Contact

**👩‍💻 Neha Bharti**  
🐙 GitHub: [@neha-dev-dot](https://github.com/neha-dev-dot)  

---

## ⭐ If you found this project helpful...

Give this repository a ⭐ and feel free to fork or share!  
Your feedback and suggestions are always welcome.

---



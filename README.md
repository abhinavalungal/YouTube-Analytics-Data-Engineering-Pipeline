
# 🎥 YouTube Analytics Data Engineering Pipeline  
<br>
<br>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" alt="YouTube Logo" width="300"/>
</p>

<br>


## 📌 Project Overview  
An end-to-end **cloud-based data engineering pipeline** built on **AWS** to analyze **YouTube trending video data**.  
The project covers **data ingestion, ETL, storage in S3, querying with Athena, and visualization with QuickSight**.  

---

## 🚀 Project Workflow  

### 🔹 Data Ingestion  
- Collected **1M+ daily YouTube trending records** across **10+ regions**.  
- Designed **batch ingestion pipeline** to handle large-scale streaming-like data.  
- Stored raw and curated layers in **Amazon S3 (partitioned for scalable analytics)**.  

### 🔹 ETL with AWS Glue & PySpark  
- Automated **ETL workflows** with **AWS Glue** and **PySpark**.  
- Performed cleaning & transformations:  
  - Standardized video metadata fields.  
  - Structured key metrics (**views, likes, comments, categories**).  
  - Ensured schema consistency across regions.  

### 🔹 Data Storage & Querying  
- Designed **raw, processed, and curated layers** in S3 (following data lake architecture).  
- Queried datasets using **Amazon Athena** with optimized partitions.  

### 🔹 Visualization & Analytics  
- Built **QuickSight dashboards** for business insights:  
  - **Regional trends** in YouTube popularity.  
  - **Top-performing categories** by engagement.  
  - **Engag**

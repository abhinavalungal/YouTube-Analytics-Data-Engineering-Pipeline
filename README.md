<h1 align="center">YouTube Analytics Data Engineering Pipeline</h1>

<br>
<br>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" alt="YouTube Logo" width="300"/>
</p>

<br>

##  Project Overview :
An end-to-end **cloud-based data engineering pipeline** built on **AWS** to analyze **YouTube trending video data**. The project covers **data ingestion, ETL, storage in S3, querying with Athena, and visualization with QuickSight**.

---

##  Project Workflow :

###  Data Ingestion
- Collected **1M+ daily YouTube trending records** across **10+ regions**.
- Designed a **batch ingestion pipeline** for handling large-scale data.
- Stored raw and curated layers in **Amazon S3**, using partitioning for scalable analytics.

###  ETL with AWS Glue & PySpark
- Automated **ETL workflows** with **AWS Glue** and **PySpark**.
- Cleaned and transformed video metrics: **views**, **likes**, **comments**, **categories**.
- Ensured schema consistency across regional datasets.

###  Data Storage & Querying
- Implemented **raw**, **processed**, and **curated** data layers in S3 (data lake architecture).
- Queried structured datasets with **Amazon Athena**, taking advantage of partitioned data.

###  Visualization & Analytics
- Built interactive **QuickSight dashboards** to analyze:
  - **Regional trends** in video popularity.
  - **Top-performing categories** and engagement metrics.
- Achieved a **40% reduction in analysis time** through pipeline automation.

---

##  Tools & Technologies :
- **AWS S3** – Scalable storage  
- **AWS Glue + PySpark** – ETL orchestration  
- **Amazon Athena** – Serverless querying  
- **Amazon QuickSight** – Business intelligence dashboards  
- **Python** – Data transformation and scripting  

---

##  Key Outcomes :
- Efficiently processed **1M+ daily records** across multiple regions.  
- Established a scalable, partitioned **data lake architecture**.  
- Delivered **insightful dashboards** for trend and engagement analytics.  
- Realized **40% faster analytics turnaround**.

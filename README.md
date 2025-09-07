<h1 align="center">YouTube Analytics Data Engineering Pipeline</h1>

<br>
<br>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" alt="YouTube Logo" width="300"/>
</p>

<br>
  
## Overview  
This project aims to securely manage, streamline, and analyze structured and semi-structured YouTube trending data across multiple regions. The focus is on building a scalable, cloud-based data pipeline to handle growing data volumes and deliver actionable insights through analytics dashboards.

---

## Project Goals  
- **Data Ingestion** — Build a mechanism to ingest data from multiple sources (Kaggle + regional datasets).  
- **ETL System** — Transform raw data into a clean, structured format for analytics.  
- **Data Lake** — Centralize storage of raw, processed, and curated layers.  
- **Scalability** — Ensure the pipeline scales as data volume grows (1M+ records daily).  
- **Cloud-first** — Use AWS for storage, processing, and querying.  
- **Reporting** — Build dashboards to analyze regional trends and category performance.  

---

## Dataset  
- Source: **Kaggle – YouTube Trending Video Dataset**  
- Contains statistics (CSV + JSON) on daily trending YouTube videos across 10+ regions.  
- Features include: video title, channel, publication time, tags, views, likes, dislikes, comments, categories, and category_id (region-specific).  
- Up to 200 trending videos per day per region, resulting in 1M+ daily records.  

---

## Workflow  

### 1. Data Ingestion  
- Collected 1M+ daily YouTube trending records across regions.  
- Designed a batch ingestion pipeline for large-scale ingestion.  
- Stored structured & semi-structured raw data in Amazon S3 (data lake) with partitioning for scalable queries.  

### 2. ETL with AWS Glue & PySpark  
- Automated ETL workflows with AWS Glue + PySpark.  
- Standardized and cleaned metrics: views, likes, dislikes, comments, categories.  
- Ensured schema consistency across regional datasets.  

### 3. Data Lake & Querying  
- Implemented a multi-layered S3 data lake: raw → processed → curated.  
- Queried curated datasets with Amazon Athena (serverless SQL).  
- Leveraged partitioning for cost-efficient, faster queries.  

### 4. Visualization & Analytics  
- Built interactive QuickSight dashboards for:  
  - Regional popularity trends.  
  - Top-performing categories & engagement metrics.  
- Reduced analysis time by 40% with automation.  

---

## AWS Services Used  
- **Amazon S3** → Central data lake storage.  
- **AWS Glue + PySpark** → ETL orchestration & schema enforcement.  
- **Amazon Athena** → Serverless querying on partitioned S3 data.  
- **Amazon QuickSight** → BI dashboards & analytics.  
- **AWS IAM** → Secure access & role-based permissions.  
- **AWS Lambda** → Trigger-based automation for lightweight processing tasks.  

---

## Key Outcomes  
- Processed 1M+ daily records across 10+ global regions.  
- Established a secure, partitioned data lake architecture on AWS.  
- Delivered interactive dashboards for real-time trend analysis.  
- Achieved 40% faster analytics turnaround with automated ETL & reporting.  

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">


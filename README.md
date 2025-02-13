# Semiconductor Market Data AWS Pipeline

## 🚀 Project Overview
This project involves the design and deployment of a **cloud-based data pipeline** to automate the extraction, transformation, and loading (ETL) of global semiconductor market data. The pipeline is built using **Python, AWS (Lambda, S3, Redshift, EC2, EventBridge)** and visualized in **Power BI**. It is **deployed and automated** to update data every 15 days.

## 🏗️ Workflow
1. **Data Extraction (Python)**: Scraped semiconductor market data from a website using `requests` and `BeautifulSoup`.
2. **Data Cleaning & Transformation (Python, Pandas)**: Processed and cleaned raw data using `pandas`.
3. **Cloud Storage (AWS S3)**: Uploaded cleaned data as CSV to **AWS S3** bucket.
4. **Pipeline Automation (AWS Lambda + EventBridge)**: Automated pipeline execution using **Lambda**, scheduled every 15 days with **EventBridge**.
5. **Data Warehousing (Amazon Redshift)**: Loaded S3 data into **Amazon Redshift Serverless** for querying and analysis.
6. **Visualization (Power BI)**: Connected **Power BI** to **Redshift** for real-time data visualization.

## 🔑 Key Features
- **Fully Automated ETL Pipeline** leveraging **AWS Cloud Services**.
- **Cloud-Based Storage & Data Processing** with **S3** and **Redshift**.
- **Scheduled Data Updates** via **EventBridge**.
- **Python for ETL Processing**: Data extraction, cleaning, and transformation.
- **Power BI Dashboard** connected to **Redshift** for real-time visualization.

## 🛠️ Tools & Technologies
| **Category**      | **Tools/Services**                                         |
|-------------------|-------------------------------------------------------------|
| Programming       | Python (requests, BeautifulSoup, pandas, boto3)             |
| Cloud Services    | AWS Lambda, AWS S3, Amazon Redshift, AWS EC2, EventBridge   |
| Database/SQL      | Redshift, SQL                                                |
| Visualization     | Power BI                                                     |
| Automation        | EventBridge, Lambda Scheduling                              |

## 📊 Key Insights from Data Analysis
- **2024 Market Growth:** Global semiconductor sales hit **$627.6B**, a **19.1% YoY increase**.
- **Market Leaders:** TSMC holds **54% market share**, NVIDIA dominates AI chips with **88% share**.
- **AI Demand:** AI-specific chips account for **20% of total sales**, driven by OpenAI’s $500B infrastructure investments.

## 📂 Project Structure

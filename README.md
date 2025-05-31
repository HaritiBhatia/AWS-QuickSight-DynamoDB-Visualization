# AWS-QuickSight-DynamoDB-Visualization
**Tools Used**: AWS QuickSight, DynamoDB, Lambda, Athena, IAM, JSON  


---

## 📌 Project Overview

This project demonstrates how to build a real-time data visualization dashboard using **AWS QuickSight** connected to **DynamoDB**, with **Athena + Lambda** integration for querying and ingesting semi-structured data.

---

## 🎯 Objective

To create an automated, scalable dashboard that visualizes product inventory and order data stored in DynamoDB, enabling dynamic filtering and reporting for business stakeholders.

---

## 🔧 Architecture & Workflow

### 1. Data Source
DynamoDB table storing JSON-based order records (product ID, quantity, timestamp, location).



### 2. Data Ingestion & Querying
Integrated **AWS Lambda** and **Athena** with the **DynamoDB connector** to convert JSON records into queryable tabular data using Glue Data Catalog.



### 3. IAM Configuration
Created service roles with appropriate permissions for QuickSight, Lambda, and Athena to securely access and query data.



### 4. Visualization with QuickSight
Created a dashboard with the following features:
- Bar and line charts for inventory trend over time
- Geographic heatmap of product demand by region
- Filters for product category, date range, and location



### 5. Automation
Enabled automatic refresh of datasets and linked scheduled queries from Athena to update QuickSight visuals.

---

## 📈 Outcome & Impact

- Enabled near real-time visualization of inventory data without manual exports
- Improved decision-making around product distribution and stock levels
- Demonstrated end-to-end pipeline from raw JSON data to business-ready dashboards using fully managed AWS services

---

## 📂 Deployment

This project was built entirely within the AWS Console and is not available as a public GitHub repository due to infrastructure-specific components.

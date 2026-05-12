# End-to-End Loan Risk Analytics & Data Pipeline

## 🎯 Project Overview
This project delivers a complete end-to-end business intelligence solution. I engineered a hybrid data pipeline that automates the flow of information from a local **SQL Server** database to the **Power BI Service** using **On-premises Data Gateways** and **Dataflows**. The project culminates in an interactive dashboard that identifies key risk drivers for loan defaults.

## 🏗️ The End-to-End Workflow
1.  [cite_start]**Data Ingestion:** Initialized a `Loan` database in **SQL Server** to host raw borrower data.
2.  **Hybrid Connectivity:** Established a secure bridge between the local database and the cloud using an **On-premises Data Gateway**.
3.  **Cloud ETL (Dataflows):** Developed **Power BI Dataflows** to perform centralized data cleaning and transformation. This ensures that the heavy processing is handled in the cloud, resulting in a faster, more efficient reporting layer.
4.  [cite_start]**Advanced Modeling:** Connected the Power BI report to the Dataflow and implemented a robust library of **DAX measures** to conduct demographic segmentation and time-series analysis[cite: 4].

## 📊 Analytical Highlights (DAX)
The project utilizes advanced DAX to generate actionable financial insights:
* [cite_start]**Dynamic Binning:** Segmented borrowers into `Income Brackets`, `Credit Score Bins`, and `Age Groups` for targeted risk analysis[cite: 4].
* [cite_start]**Performance Tracking:** Built Year-over-Year (YOY) measures to track changes in default frequency and total loan amounts[cite: 4].
* [cite_start]**Risk Metrics:** Calculated `Default Rate by Employment type` and `Default Rate by Year` to pinpoint specific portfolio vulnerabilities[cite: 4].

## 📁 Repository Contents
* `DataFlow.pbix` - The final interactive analytics dashboard.
* [cite_start]`DAX_Formulas.md` - Complete documentation of the analytical logic used[cite: 4].
* [cite_start]`SQL_Setup.sql` - Script for database and table initialization.
* [cite_start]`Loan_default.csv` - Sample dataset for testing and replication[cite: 2].

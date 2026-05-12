# Strategic Loan Risk Analytics & Hybrid Pipeline

## 📊 Business Problem & Solution
Financial institutions need scalable ways to monitor loan health across different environments. I developed this end-to-end solution to automate the transition of raw data from a local **SQL Server** into a high-performance **Power BI** dashboard. This project solves the challenge of maintaining "Live" cloud reports while utilizing on-premises data storage.

## ⚙️ Engineering & Architecture
I implemented a multi-layered architecture to ensure data integrity and system performance:
* **The Source:** Managed a dedicated database in **SQL Server** to host a dataset of over 250,000 loan records.
* **The Bridge:** Integrated an **On-premises Data Gateway** to facilitate a secure, automated connection between local hardware and the cloud.
* **The Pipeline:** Engineered **Power BI Dataflows** for centralized ETL. By moving the heavy lifting (data cleaning and transformation) into the cloud, I optimized the dashboard's refresh speed and ensured a single source of truth.
* **The Intelligence:** Developed a robust semantic model using complex **DAX** to extract predictive patterns from raw data.

## 🧠 Analytical Deep-Dive (DAX)
Instead of basic aggregations, I built advanced measures to reveal business growth and risk trends:
* **Demographic Profiling:** Created logic-based bucketing for `Income Brackets`, `Credit Score Bins`, and `Age Groups` to identify high-risk segments.
* **Time-Intelligence:** Designed **Year-over-Year (YOY)** growth measures to track fluctuations in loan defaults and total portfolio volume.
* **Contextual Risk:** Utilized specialized filtering to calculate **Default Rates by Employment Type**, providing a granular view of risk across different job sectors.

## 📁 Repository Map
* **`DataFlow.pbix`**: The primary reporting file containing the data model and interactive visuals.
* **`DAX_Codebase.md`**: A clean, documented list of every formula used—proving my coding standards.
* **`SQL_Query.sql`**: The script used to initialize the source database.
* **`Loan_Dataset.csv`**: Sample data used for the pipeline demonstration.

## 💡 Professional Value
This project demonstrates my proficiency in **Data Engineering** (Gateways/Dataflows) and **Data Analysis** (DAX/SQL). It proves my ability to design, deploy, and document an enterprise-level data system.

## 📸 Dashboard Preview
<img width="1886" height="1060" alt="image" src="https://github.com/user-attachments/assets/7dc664e3-fc8a-4df9-9d11-3268713b8d08" />


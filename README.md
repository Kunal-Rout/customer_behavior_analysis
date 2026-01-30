# 👨🏻‍💻Customer Behavior Data Analyst Portfolio Project

## 📌 Project Overview
This project simulates a corporate-grade data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence. The pipeline covers everything from initial data ingestion to executive-level reporting.

The workflow is divided into four key stages:
* **Data Preparation & EDA (Python):** Cleaning and transforming raw datasets.
* **Data Analysis (SQL):** Simulating business transactions and extracting segment-specific insights.
* **Visualization (Power BI):** Building interactive dashboards for data-driven decision-making.
* **Strategic Reporting:** Summarizing findings and actionable business recommendations.
  
<img width="4872" height="2656" alt="image" src="https://github.com/user-attachments/assets/6b3820ef-9226-4158-b37d-281331abc22b" />



---

## 🛠️ Tech Stack & Tools
* **Language:** Python (Pandas, NumPy, SQLAlchemy)
* **Database:** PostgreSQL 
* **Visualization:** Power BI
* **Presentation:** Gamma AI
* **Reporting:** MS Word

---

## 🚀 Project Workflow

### 1. Data Preparation & EDA (Python)
**File:** `Customer_Shopping_Behavior_Analysis.ipynb`  
In this phase, I performed the core ETL (Extract, Transform, Load) operations:
* **Data Import:** Loading raw customer datasets.
* **Exploration:** Identifying patterns, missing values, and statistical outliers.
* **Data Cleaning:** Normalizing formats and handling inconsistencies.
* **Database Connection:** Using Python to establish a connection and load the processed data directly into the SQL Server.

### 2. Business Logic & Querying (SQL)
**File:** `customer_behavior_sql_queries.sql`  
Once the data was structured in the database, I executed complex queries to simulate real-world business requests:
* **Customer Segmentation:** Categorizing users based on purchase history.
* **Loyalty Analysis:** Measuring the impact of loyalty programs on retention.
* **Purchase Drivers:** Identifying which factors most influence high-value transactions.

### 3. Interactive Visualization (Power BI)
**File:** `customer_behavior_dashboard.pbix`  
Connecting the SQL database to Power BI to create a dynamic visual ecosystem:
* **Dynamic Dashboards:** Real-time filtering by demographics and behavior.
* **Trend Mapping:** Highlighting seasonal patterns and purchase shifts.
* **Stakeholder View:** Simplified KPI tracking (AOV, Retention Rate, etc.).

### 4. Report & Presentation
* **Project Report:** A detailed document summarizing the methodology, data limitations, and final findings.
* **Presentation Deck:** Created using **Gamma AI** to visually communicate insights and "Next Step" recommendations to stakeholders.

---

## 📁 Repository Structure
```text
├── Notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb  # Python Cleaning & SQL Loading
├── SQL_Scripts/
│   └── customer_behavior_sql_queries.sql          # Business Logic Queries
├── Dashboards/
│   └── customer_behavior_dashboard.pbix           # Power BI Dashboard file
├── Reports/
│   ├── Project_Report.md                          # Detailed Findings
│   └── Presentation_Link.txt                      # Link to Gamma AI Slides
└── Data/                                          # (Optional) Raw data files


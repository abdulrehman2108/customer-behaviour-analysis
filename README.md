Customer Behaviour Analysis 
This project focuses on the end-to-end data pipeline process—from raw data cleaning to structured storage and analytical reporting. The goal is to transform raw customer datasets into actionable insights using Python for processing and MySQL for robust data management.

📊 Current Project Status: ETL Phase
The project has successfully moved through the initial data engineering stages:

1. Requirements & Problem Logic
Document: Business Problem Document.pdf

Goal: Defining KPIs such as purchase frequency, customer demographics, and revenue metrics to guide the cleaning process.

2. Data Cleaning & Transformation (Python)
Script: customer_analysis.ipynb

Operations: * Identifying and handling null values and duplicates.

Standardizing data formats (dates, categorical strings) for SQL compatibility.

Using Pandas for high-level data manipulation.

3. Database Integration (SQLAlchemy)
Action: Established a connection between the Python environment and a MySQL database.

Process: Using sqlalchemy to automate the loading of cleaned DataFrames into SQL tables. This ensures the data is structured, indexed, and ready for complex relational queries.

🛠️ Technical Toolkit
Processing: Python (Pandas, NumPy)

Database Engine: MySQL

Connectivity: SQLAlchemy, PyMySQL

Analysis Environment: Jupyter Notebook

📈 Roadmap
[ ] SQL-Based Analysis: Writing complex queries (Joins, CTEs, Window Functions) in MySQL to extract behavioral trends.

[ ] Data Visualization: Connecting the MySQL database to a visualization tool (like Power BI, Tableau, or Seaborn) to build a dashboard.

[ ] Optimization: Implementing database indexing to improve query performance on large customer datasets.

📂 File Directory
customer_analysis.ipynb: Contains the Python-based cleaning logic and the SQLAlchemy export script.

Business Problem Document.pdf: Outlines the analytical objectives and business context.

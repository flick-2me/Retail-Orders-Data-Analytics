# 🛒 Retail Orders End-to-End Data Analysis

## 📌 Project Overview
This project demonstrates an end-to-end data analytics pipeline that extracts retail sales data from Kaggle, performs data cleaning and transformation using Python, loads the processed data into Microsoft SQL Server, and generates actionable business insights through advanced SQL analysis.

The project showcases key data engineering and analytics concepts including ETL processes, feature engineering, database integration, and business intelligence reporting.

## 🛠️ Tech Stack

**Programming Languages**
* Python
* SQL

**Libraries & Tools**
* Pandas
* SQLAlchemy
* Kaggle API
* ZipFile

**Database**
* Microsoft SQL Server

**Dataset**
* Retail Orders Dataset (Kaggle)

---

## 🚀 Project Workflow

### 1️⃣ Data Extraction
* Downloaded retail order data using the Kaggle API.
* Extracted compressed dataset files automatically using Python.

### 2️⃣ Data Cleaning & Transformation
* Handled missing values and standardized null representations.
* Renamed columns using `snake_case` naming conventions.
* Converted date columns into `datetime` format.
* Engineered new business metrics such as Profit.
* Removed redundant columns to improve storage efficiency.

### 3️⃣ Data Loading
* Connected Python to Microsoft SQL Server using SQLAlchemy.
* Loaded transformed data into the `df_orders` table.
* Implemented an ETL workflow for seamless database integration.

### 4️⃣ Data Analysis
Performed advanced SQL analysis using:
* Common Table Expressions (CTEs)
* Window Functions
* Aggregate Functions
* Ranking Functions
* Date Functions

---

## 📊 Business Problems Solved

1. **Top Revenue Generating Products**
   Identified the top 10 products contributing the highest sales revenue.
2. **Regional Product Performance**
   Determined the top 5 highest-selling products within each region.
3. **Year-over-Year Sales Growth**
   Compared monthly sales performance between 2022 and 2023.
4. **Category Sales Trends**
   Identified the highest-performing month for each product category.
5. **Profit Growth Analysis**
   Analyzed sub-categories with the highest profit growth in 2023 compared to 2022.

---

## 📈 Key Skills Demonstrated
* Data Cleaning & Preprocessing
* ETL Pipeline Development
* SQL Query Optimization
* Business Analytics
* Database Management
* Feature Engineering
* Data Transformation
* Sales & Revenue Analysis

---

## 📂 Project Structure

```text
Retail-Orders-Analysis/
│
├── README.md
├── orders_data_analysis.py
├── sql_code.sql
│
├── Dataset/
│   └── orders.csv

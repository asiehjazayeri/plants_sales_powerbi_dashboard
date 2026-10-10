🌿 Plants Sales Analytics | SQL Server & Power BI

📊 Project Overview
This project analyzes sales data from a Canadian plants and trees retail business using SQL Server and Power BI.
The project begins with SQL-based data preparation, including data type corrections, data quality checks, validation of table relationships, and the creation of reusable SQL Views. The prepared data is then connected to Power BI for data modeling, DAX development, and interactive dashboard reporting.
The goal is to transform raw business data into a reliable analytical dataset and provide insights into sales performance across products, customers, time, and geography.

🗄️ SQL Data Preparation
SQL Server was used to prepare and validate the data before Power BI analysis.
Key SQL operations include:
- Importing raw CSV files into SQL Server.
- Correcting data types and converting numeric fields.
- Cleaning and standardizing sales data through vw_Sales_Clean.
- Checking missing values and invalid records.
- Validating relationships between sales and related tables.
- Joining Sales with Products, Customers, Sellers, and Shipping.
- Creating vw_Sales_Analytics for analysis-ready data.
- Performing sales analysis using aggregate functions, joins, grouping, and sorting.
The SQL work is documented in the repository's SQL folder.

### DataBase Structure

![01_Database_structure](./SCREENSHOTS/01__Database_Structure.png)
---
![02_Data_Quality_Check](./SCREENSHOTS/02_Data_Quality_Check.png)
---
![03_Sales_Clean_View](./SCREENSHOTS/03_Sales_Clean_View.png)
---
![04_Sales_By_Category](./SCREENSHOTS/04_Sales_By_Category.png)
---
![05_Sales_Analytics_View](./SCREENSHOTS/05_Sales_Analytics_View.png)
---
![06_PowerBi_Executive_Overview](./SCREENSHOTS/06_PowerBi_Executive_Overview.png)

## 🚀 Dashboard Features

* Executive KPI Monitoring
* Interactive Slicers
* Dynamic KPI Cards
* Year-over-Year Analysis
* Sales Target Achievement
* Root Cause Analysis
* Geographic Sales Analysis
* Product & Customer Insights
* Dynamic Insight Measures
* Custom Report Tooltips
* Performance-Optimized Data Model

---

## 📑 Dashboard Pages

### 🏠 Home

Navigation page providing access to the main analytical sections of the report.

### 📈 Executive Overview

High-level business KPIs, sales performance, profitability, and trends.

### 🔍 Root Cause Analysis

Uses a **Decomposition Tree** to investigate the factors driving sales performance.

### 🌿 Product & Customer Insights

Analyzes product performance and customer-related sales patterns.

### 🗺 Geographic Sales

Provides interactive province-level geographic analysis of sales performance.

---

## 📌 Key Performance Indicators

* Total Sales
* Gross Profit
* Gross Margin %
* YoY Growth
* Sales Target Achievement
* Top Province
* Highest Sales Category
* Best-Selling Product
* Best Sales Month
* Best Sales Year

---

## 🛠 Tools & Technologies

* Microsoft Power BI Desktop
* DAX
* Power Query
* Tabular Editor
* Bravo for Power BI
* DAX Studio

---

## ⚡ Performance Optimization

The report has been optimized using:

* Star Schema Data Model
* Optimized DAX Measures
* Bravo for Power BI
* DAX Studio / VertiPaq Analyzer
* Custom Report Tooltips
* Organized Measures
* Removal of Unused Objects

---

## 📸 Dashboard Preview

### 🏠 Home

![Home](./SCREENSHOTS/Home.png)

### 📈 Executive Overview

![Executive Overview](./SCREENSHOTS/Executive%20Overview.png)

### 🔍 Root Cause Analysis

![Root Cause Analysis](./SCREENSHOTS/Root%20Cause%20Analysis.png)

### 🌿 Product & Customer Insights

![Product & Customer Insights](./SCREENSHOTS/PageProduct%20%26%20Customer.png)

### 🗺 Geographic Sales

![Geographic Sales](./SCREENSHOTS/Geographic%20Sales.png)


## 💡 Key Business Insights

The dashboard uses **dynamic DAX-driven insights** to automatically translate sales metrics into concise business findings.

### 📍 Leading Province

**Ontario** is the leading province, contributing **21% of total sales**.

### 🌳 Top-Performing Category

**Ornamental Trees** is currently the best-performing product category.

### 🌸 Seasonal Performance

**Spring accounts for 59% of total annual sales**, highlighting a strong seasonal concentration in the business.

### 📈 Year-over-Year Performance

The current report context shows **0.0% YoY growth**, indicating stable performance compared with the previous year.

### ⚡ Dynamic Executive Insight

A consolidated executive insight dynamically combines:

* Top-performing province
* Province contribution to total sales
* Best-performing product category
* Year-over-year sales performance

The insight updates dynamically according to the report's filter context, allowing users to explore changing business results interactively.

### 🧠 DAX Techniques Used

The dynamic insights use advanced DAX concepts including:

* `TOPN`
* `ADDCOLUMNS`
* `VALUES`
* `MAXX`
* `CALCULATE`
* `DATEADD`
* `DIVIDE`
* `SELECTEDVALUE`
* `SWITCH`
* Dynamic text generation with `FORMAT`

### 📋 Documentation

![Documentation](./SCREENSHOTS/Documentation.png)
---

## 📚 Documentation

Additional project documentation, including the data model, color theme, and project presentation, is available in the **Documentation** folder.

### Data Model

![Data Model](./Documentation/Data-Model.png)

### Color Theme

![Color Theme](./Documentation/Color-Theme.png)

📄 [View Project Presentation (PDF)](./Documentation/SALES%20ANALYTICS%20DASHBOARD%20PLANTS.pdf)
---

## 💡 Key Skills Demonstrated

* Data Modeling
* DAX Development
* Time Intelligence
* Power Query
* Dashboard Design
* Business Intelligence
* Data Visualization
* Business Analysis
* Performance Optimization

---

## 🎯 Project Objective

The objective of this dashboard is to transform sales data into actionable business insights by providing stakeholders with an interactive environment for monitoring performance, identifying trends, and exploring the underlying drivers of sales.


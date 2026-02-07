# E-Commerce Sales Data Analysis 

# Project Overview

This project analyzes an E-Commerce dataset to uncover sales trends, customer purchasing behavior, product performance, and revenue distribution over time. The goal is to transform raw transactional data into actionable business insights using Python, SQL, and Power BI.

Performed end-to-end analysis using SQL for querying and Power BI for visualization to derive business insights on revenue, customers, and products.

# Dataset Description

The dataset contains transactional data from an online retail store, where each row represents a product purchased as part of an invoice.

# Key Columns
1. **InvoiceNo** – Unique transaction identifier
2. **InvoiceDate** – Date and time of purchase
3. **CustomerID** – Unique customer identifier
4. **Description** – Product description
5. **Quantity**– Number of units purchased
6. **UnitPrice** – Price per unit
7. **Country**– Customer’s country

# Tools & Technologies Used
- **Python** (Pandas)
- **SQLite** for querying and analysis
- **Power BI** for interactive dashboards
- **Jupyter Notebook** for documentation and analysis

# Key Steps

* Loaded CSV data and resolved data quality issues (duplicate columns, date format errors)
* Created SQL tables and executed business-focused queries
* Calculated KPIs: Total Revenue, Total Orders, Total Customers, AOV
* Connected SQLite database to Power BI
* Designed an interactive dashboard with filters and drill-downs


# Data Cleaning & Preprocessing

The following steps were performed to ensure data accuracy and reliability:
- Removed rows with missing CustomerID
- Removed records with: Negative or zero Quantity ,Zero or negative UnitPrice
- Converted InvoiceDate to datetime format

- Created a new Revenue column
(Revenue = Quantity × UnitPrice)

- Extracted time-based features:
Year,Month,Month Name,Day of Week


# Exploratory Data Analysis (EDA)
*Key analyses performed include:
- Monthly revenue trends to identify seasonality
- Revenue distribution by country
- Top-selling and top revenue-generating products
- Customer-level revenue contribution
- Weekday vs weekend sales analysis


# Key Insights
- A small group of customers contributes a significant portion of total revenue
- Revenue shows clear seasonal patterns with peak sales in specific months
- Certain products generate high revenue despite lower sales volume
- Most revenue comes from a primary country, with scope for international growth
- Weekday sales outperform weekend sales, indicating business-day shopping behavior

# Dashboard (Power BI)
An interactive Power BI dashboard was created to visualize:
- Total Revenue, Orders, Customers, and AOV 
- Monthly revenue trends
- Top products and top customers
- Country-wise revenue distribution
- Weekly sales performance

# Conclusion
This project demonstrates a complete data analytics pipeline from raw data cleaning to insights and visualization—using real-world e-commerce data. 

# Author
Devika Madupu
M.Sc Computer Science | Aspiring Data Analyst

# License
This project is for learning and demonstration purposes.

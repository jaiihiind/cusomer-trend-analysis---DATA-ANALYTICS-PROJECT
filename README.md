# 📊 Customer Shopping Behavior Analysis — Customized Portfolio Project

An end-to-end customer analytics project built with **Python, SQL, and Power BI** to understand purchasing behavior, customer segments, discounts, subscriptions, product performance, and revenue patterns.

> **Project note:** This repository is a customized and extended version of an MIT-licensed open-source project. The original project was used as the technical starting point; I modified the analysis, SQL questions, documentation, and implementation details to create my own portfolio version. The original MIT license and attribution are retained.

## 🎯 Business Objective

The objective is to turn customer transaction data into practical business insights that can help a retail business:

- Understand who generates the most revenue
- Identify important customer segments
- Evaluate subscription and discount behavior
- Compare product/category performance
- Understand purchase frequency and customer loyalty
- Support decisions through an interactive Power BI dashboard

## 🧰 Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python / Pandas** | Data cleaning, transformation and exploratory analysis |
| **SQL / PostgreSQL** | Business-question analysis and customer segmentation |
| **Power BI** | Interactive dashboard and KPI visualization |
| **Jupyter Notebook** | Reproducible analysis workflow |

## 📁 Project Structure

```text
Customer Shopping Behavior Analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── Customer Shopping Behavior Analysis.pdf
├── Business Problem Document.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
├── ANALYST_NOTES.md
├── LICENSE
└── README.md
```

## 🔎 What I Worked On

### 1. Data Preparation in Python
- Loaded and inspected the raw customer dataset
- Checked data types, null values, and descriptive statistics
- Imputed missing review ratings using category-level medians
- Standardized column names for easier SQL usage
- Created `age_group`
- Converted purchase-frequency labels into day-based numeric values
- Removed a redundant promo-code field after validating its relationship with discount usage

### 2. SQL Business Analysis
The original SQL analysis was extended with additional questions focused on customer value, category performance, repeat purchasing, discount behavior, and purchase frequency.

Examples:
- Revenue by gender and age group
- Subscriber vs. non-subscriber spending
- Product discount rates
- Customer loyalty segmentation
- Top products within each category
- High-value repeat customers
- Category revenue contribution
- Purchase-frequency analysis

### 3. Power BI
The Power BI dashboard is used to communicate:
- Total revenue
- Customer count
- Average purchase amount
- Subscription mix
- Category performance
- Customer demographics
- Product and purchasing trends

### 4. My Analytical Enhancements
I added a dedicated **Analyst Enhancements** section to the notebook and additional SQL queries so the project demonstrates my own analytical decisions rather than being only a direct copy of the original workflow.

## 📌 Key Findings from the Dataset

Based on the supplied dataset of **3,900 customer records**:

- Total purchase revenue: **$233,081**
- Average purchase amount: **$59.76**
- Clothing generated the highest category revenue at approximately **$104.3K**
- Male customers generated approximately **$157.9K** in revenue
- Non-subscribers generated more total revenue than subscribers in this dataset, although the groups have similar average purchase values
- Purchases with discounts had a slightly lower average purchase amount than purchases without discounts

These observations are used as examples of how raw transactions can be translated into business recommendations.

## ▶️ How to Run

### Python
Open:

```text
Customer_Shopping_Behavior_Analysis.ipynb
```

Place the notebook and CSV in the same directory and run the cells in order.

### SQL
1. Load the processed dataset into PostgreSQL.
2. Create a table named `customer`.
3. Run:

```text
customer_behavior_sql_queries.sql
```

### Power BI
Open:

```text
customer_behavior_dashboard.pbix
```

Refresh the data source if your local file/database path is different.

## 💡 Portfolio Takeaway

This project demonstrates an end-to-end workflow:

**Raw Data → Data Cleaning → EDA → Business Questions → SQL Analysis → Dashboard → Insights → Recommendations**

The emphasis is not only on writing queries or charts, but on connecting the analysis to business decisions.

## 📜 License & Attribution

This project is based on and extends an MIT-licensed repository by **Amlan Mohanty**.

The original MIT license and copyright notice are retained in this repository. My changes include customized documentation, additional SQL analysis, notebook enhancements, and implementation improvements.

## 👤 Project Contributor

**RISHAV RAY**

Data Analytics Portfolio Project  
Skills demonstrated: **Python • SQL • Power BI • EDA • Business Analysis**

> Project contributor: **RISHAV RAY**

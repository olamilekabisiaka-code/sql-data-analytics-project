# sql-data-analytics-project

Welcome to the **Data Analytics Project** repository
This project demonstrates data analytics skills using SQL, including data cleaning, transformation, and exploratory analysis.


Here’s a **clean, professional README.md** tailored to your SQL project. You can copy and paste this directly into your GitHub repo:

---

# 📊 SQL Data Analytics Project

## 📌 Overview

This project showcases my SQL skills in data analysis by working with a sales dataset. It focuses on extracting insights, analyzing trends, and building reusable data models using advanced SQL techniques.

The project includes data exploration, aggregation, segmentation, and the creation of reporting views to support business decision-making.

---

## 🎯 Objectives

* Analyze sales performance over time (yearly and monthly)
* Identify customer behavior and segmentation
* Evaluate product and category performance
* Perform cumulative and trend analysis
* Build structured views for reporting

---

## 🗂️ Dataset Structure

The project uses a star schema with the following tables:

* **fact_sales** – transactional sales data
* **dim_customers** – customer details
* **dim_products** – product information

---

## 🛠️ Key SQL Techniques Used

* Aggregations (`SUM`, `COUNT`, `AVG`)
* Joins (`LEFT JOIN`)
* Date functions (`YEAR`, `MONTH`, `DATETRUNC`)
* Window functions (`SUM OVER`, `AVG OVER`, `LAG`)
* Common Table Expressions (CTEs)
* Case statements for segmentation
* Views for reporting

---

## 📈 Analysis Performed

### 🔹 Time-Based Analysis

* Yearly sales performance
* Monthly sales trends
* Combined year-month breakdown
* Running totals and moving averages

### 🔹 Product Performance

* Year-over-year product sales comparison
* Performance vs average sales
* Product segmentation (High, Mid, Low performers)

### 🔹 Category Contribution

* Total sales by category
* Percentage contribution to overall revenue

### 🔹 Customer Segmentation

Customers are grouped based on:

* Spending behavior
* Lifespan

Segments:

* **VIP** – High spenders with long engagement
* **Regular** – Moderate spenders
* **New** – Recently acquired customers

### 🔹 Product Segmentation

Products are grouped by:

* Cost ranges
* Sales performance tiers

---

## 🧾 Views Created

### 🟡 `gold_customers`

A customer-focused report including:

* Demographics (age, age group)
* Purchase behavior
* Customer segmentation
* Recency, lifespan
* Average order value and monthly spend

---

### 🔵 `gold_products`

A product-focused report including:

* Product categories and cost
* Sales performance
* Product segmentation
* Recency and lifespan
* Revenue metrics

---

## 🚀 Key Insights (Example)

* Sales trends vary significantly across months and years
* A small percentage of customers contribute a large share of revenue (VIP segment)
* Certain product categories dominate overall sales
* High-performing products generate disproportionately higher revenue

---

## 📌 How to Use

1. Load the dataset into your SQL environment
2. Run the queries step by step
3. Create the views (`gold_customers`, `gold_products`)
4. Use the views for reporting or visualization tools

---

## 🔧 Tools Used

* SQL Server Management Studio (SSMS)


---

## 💡 Future Improvements

* Integrate with Power BI for dashboards
* Add more advanced KPIs (retention rate, churn)
* Optimize queries for performance
* Automate data pipeline

---

## 👤 Author

**ISIAKA Habib Olamilekan**

---


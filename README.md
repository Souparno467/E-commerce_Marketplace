# Strategic Analytics Using the Olist Brazilian E-Commerce Dataset

**Transforming E-Commerce Data into Business Intelligence Using Excel, SQL, and Power BI**

---

# Project Overview

In today's digital economy, e-commerce platforms generate enormous amounts of transactional data. However, raw data alone provides little business value unless it is transformed into actionable insights.

This project uses the **Olist Brazilian E-Commerce Dataset** to demonstrate how business intelligence tools can convert raw transactional data into meaningful business insights.

Using **Microsoft Excel**, **MySQL**, and **Power BI**, this project performs data cleaning, SQL analysis, KPI development, and interactive dashboard creation to support data-driven business decisions.

The objective is to help business leaders understand customer behaviour, sales performance, logistics efficiency, and seller performance through meaningful data analysis.

---

# Business Objectives

This project answers key business questions such as:

* Which product categories generate the highest revenue?
* Which sellers contribute the most to total sales?
* How do delivery delays impact customer satisfaction?
* What are customers' purchasing behaviours?
* Which regions generate the highest sales?
* How can customer retention be improved?

---

# Dataset

**Dataset:** Olist Brazilian E-Commerce Dataset

Source: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset includes information about:

* Customers
* Orders
* Order Items
* Products
* Sellers
* Payments
* Customer Reviews
* Geolocation
* Delivery Information

---

# Tools and Technologies

* Microsoft Excel
* MySQL
* Power BI
* CSV Files
* Relational Database Concepts

---

# Project Workflow

## 1. Data Cleaning (Excel)

The raw CSV files were cleaned using Microsoft Excel.

### Steps

* Open CSV files in Microsoft Excel
* Select all records (`Ctrl + A`)
* Remove duplicate records
* Apply filters
* Remove blank and null values
* Save the cleaned datasets

---

## 2. SQL Data Preparation

The cleaned datasets were imported into MySQL for analysis.

### Steps

* Create a database
* Create tables
* Import CSV files using `LOAD DATA INFILE`
* Verify imported records
* Execute SQL queries for analysis

### SQL Concepts Used

* SELECT
* WHERE
* ORDER BY
* GROUP BY
* INNER JOIN
* Aggregate Functions

---

## 3. Power BI Dashboard Development

The cleaned datasets were imported into Power BI.

### Steps

* Import all cleaned Excel files
* Create relationships using **Manage Relationships**
* Use **Auto Detect** to establish relationships
* Create calculated measures
* Build interactive dashboards

---

# Dashboard Pages

## Executive Dashboard

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value
* Total Sellers

## Sales Analysis

* Revenue by Product Category
* Monthly Sales Trend
* Top Selling Products
* Top Performing Sellers

## Customer Analysis

* Customer Purchase Behaviour
* Repeat Customers
* Customer Distribution
* Customer Review Scores

## Logistics Dashboard

* Delivery Performance
* Delivery Delays
* Shipping Time
* Order Status

---

# Key Business Insights

## Delivery Performance

Delayed deliveries are strongly associated with lower customer review scores.

**Business Impact**

* Lower customer satisfaction
* Reduced repeat purchases
* Negative impact on marketplace reputation

---

## Product Performance

A small number of product categories generate a significant share of total revenue.

**Business Opportunity**

* Increase inventory for high-demand products
* Focus marketing efforts on top-performing categories
* Improve product availability

---

## Seller Performance

A small group of sellers contributes a large proportion of marketplace revenue.

**Recommendation**

* Support high-performing sellers
* Improve inventory planning
* Develop seller incentive programmes

---

## Customer Behaviour

Repeat customers contribute significantly to long-term business value.

**Opportunity**

* Implement loyalty programmes
* Offer personalised promotions
* Conduct targeted email marketing campaigns

---

# Executive Recommendations

## 1. Improve Delivery Performance (Highest Priority)

**Reason**

Delayed deliveries are directly linked to lower customer review scores.

**Expected Impact**

* Higher customer satisfaction
* Improved ratings
* Increased repeat purchases

---

## 2. Invest in High-Performing Products and Sellers

**Reason**

A small number of products and sellers generate the majority of marketplace revenue.

**Expected Impact**

* Higher profitability
* Better inventory management
* Increased revenue

---

## 3. Strengthen Customer Retention

**Reason**

Repeat customers provide higher long-term business value.

**Recommended Actions**

* Introduce loyalty programmes
* Provide personalised offers
* Launch targeted email marketing campaigns

---

# Strategic Action Summary

| Rank | Strategic Recommendation                       | Supporting Insight                                             | Business Impact | Feasibility |
| ---- | ---------------------------------------------- | -------------------------------------------------------------- | --------------- | ----------- |
| 1    | Improve Delivery Performance                   | Lower review scores are linked to delayed deliveries           | Very High       | High        |
| 2    | Invest in High-Performing Products and Sellers | A small number of categories and sellers generate most revenue | High            | High        |
| 3    | Strengthen Customer Retention                  | Repeat customers contribute greater long-term value            | High            | Medium      |

---

# Repository Structure

```text
Olist-Ecommerce-Analytics/
│
├── Dataset/
│   ├── Raw_Data/
│   └── Cleaned_Data/
│
├── SQL/
│   └── MYSQL_Scripts.sql
│
├── PowerBI/
│   └── Olist_Dashboard.pbix
│
├── Images/
│   ├── Executive_Dashboard.png
│   ├── Sales_Dashboard.png
│   ├── Customer_Dashboard.png
│   └── Logistics_Dashboard.png
│
└── README.md
```

---

# Skills Demonstrated

* Data Cleaning
* Data Preparation
* SQL Querying
* Relational Database Management
* Data Visualisation
* Business Intelligence
* Dashboard Development
* KPI Design
* Business Analytics
* Data-Driven Decision Making

---

# Learning Outcomes

This project provided practical experience in:

* Cleaning and preparing real-world datasets
* Building relational databases
* Writing SQL queries for business analysis
* Creating interactive Power BI dashboards
* Developing KPIs and performance metrics
* Presenting business insights for decision-making

---

# Future Enhancements

* Sales Forecasting
* Customer Segmentation
* RFM (Recency, Frequency, Monetary) Analysis
* Customer Lifetime Value (CLV) Analysis
* Inventory Optimisation
* Real-Time Dashboard Integration

---

# Author

**Aditya Saha & Souparno Goswami**

Data Analytics and Artificial Intelligence Student

---

# Acknowledgements

Dataset provided by **Olist** through **Kaggle**.

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Drive Link

https://drive.google.com/drive/folders/1S8SwzdmSPnb9htOAl2MziAvFNBGdBZCo?usp=sharing


---

## License

This project is intended for educational and portfolio purposes.

# Amazon-Ecommerce-Analysis---Power-BI


# 📊 Amazon E-Commerce Analytics Dashboard
 ![Image Alt](https://github.com/Code-amar/Amazon-Ecommerce-Analysis---Power-BI/blob/2942b8b58bc6dd4f5a212583bd2995bc61ff774a/Screenshot%202026-02-28%20024806.png)

## 🚀 Project Overview

This project presents an end-to-end **data analytics solution for Amazon’s e-commerce operations**, combining **SQL, Power BI, Excel, and DAX** to extract actionable business insights.

The analysis focuses on **revenue optimization, customer segmentation, product performance, and delivery efficiency**, enabling stakeholders to make data-driven strategic decisions.

The project follows a structured analytics workflow including:
**Data Cleaning → Data Modeling → KPI Development → Visualization → Business Recommendations**

---

## 🧱 Tech Stack

* **Power BI** → Interactive dashboards & storytelling
* **MySQL** → Advanced querying, CTEs, window functions
* **Excel** → Data preprocessing and validation
* **DAX** → KPI calculations & time intelligence
* **Power Query (M Language)** → Data transformation pipeline

---

## 📂 Project Assets

| File                                   | Description                       |
| -------------------------------------- | --------------------------------- |
| `PowerBI_Project_Amar_DS.pbix`         | Final interactive dashboard       |
| `Amazon_ecommerce_amar.sql`            | SQL queries for business analysis |
| `Amazon_Ecommerce_Amar_Doc_File.docx`  | Detailed methodology & answers    |
| `Amazon E-Commerce Power BI_Amar.pptx` | Stakeholder presentation          |

---

## 📊 Business Objectives

The project was designed to answer both **objective and business-driven analytical questions**, such as:

* Revenue trends across years and categories
* Customer growth and segmentation
* Product performance and return behavior
* Delivery efficiency and wait time analysis
* Regional sales distribution
* Loyalty program design

These requirements were derived from structured problem statements and reporting expectations 

---

## 📈 Key KPIs Developed

* **Total Revenue** → ₹107M+ generated from sales 
* **Total Orders & Unique Customers**
* **Average Order Value (AOV)**
* **Average Delivery Time (~9.41 days)** 
* **Product Return Count (~31K returns)** 
* **Monthly & Yearly Growth Rates**
* **Category-wise Sales Performance**

---

## 🔍 Advanced SQL Analysis

The project includes complex SQL use cases demonstrating strong analytical capability:

* **Customer Scoring Model (Top 5 Customers)**

  * Weighted metrics: Revenue (50%), Frequency (30%), AOV (20%)
* **Month-over-Month Revenue Growth (Window Functions)**
* **Rolling 3-Month Revenue Trends (Moving Average)**
* **Customer Behavior Analysis (Order Intervals)**
* **Revenue Benchmarking (>30% above average customers)**
* **Year-over-Year Category Growth Ranking**

These queries leverage **CTEs, LAG(), DENSE_RANK(), and aggregations** for scalable analytics 

---

## 📊 Power BI Dashboard Design

The dashboard is structured into **three business-focused views**:

### 🔹 Main Dashboard

* Total revenue, customer count, and overall performance
* Category & date slicers for dynamic filtering

### 🔹 Product Analysis Tab

* Category-wise performance
* Customer satisfaction & purchase trends
* Identification of underperforming products

### 🔹 Individual Product View

* Deep dive into product-level metrics
* Revenue, ratings, category hierarchy
* Product optimization insights

These layouts were built based on stakeholder reporting requirements 

---

## 📈 Key Insights

### 💰 Revenue & Growth

* Significant revenue growth observed, especially in recent years
* 2020 showed a major increase in customer acquisition (~25K users) 

### 🛍 Product Performance

* Top categories: **Fashion, Health & Beauty, Electronics** 
* Clear gap between high-performing and underperforming products

### 👥 Customer Behavior

* ~85% customers fall into low-spending segment
* High-value customers contribute disproportionately to revenue 

### 🚚 Delivery & Satisfaction

* Faster delivery correlates with higher ratings
* “Shipped from Abroad” shows highest delivery time
* Avg rating ~2.73 indicates improvement scope 

### 🌍 Regional Insights

* North America & Africa are top-performing regions
* South America underperforms, indicating expansion opportunity 

---

## 🧠 Analytical Techniques Used

### Data Cleaning & Preparation

* Removed blank rows & irrelevant columns
* Handled null values (e.g., replaced missing return reasons)
* Fixed data types and date format inconsistencies
* Used **Power Query (M language)** for transformation

### Data Modeling

* Established **Many-to-One relationship (Orders → Customers)**
* Built star-schema-like structure for reporting 

### DAX Implementation

* Aggregations: `SUM`, `AVERAGE`, `DISTINCTCOUNT`
* Time Intelligence: `SAMEPERIODLASTYEAR`, `DATEADD`
* Iterators: `SUMX`, `AVERAGEX`
* Filter Functions: `CALCULATE`, `FILTER`

---

## 💡 Strategic Recommendations

### 🎯 Revenue Optimization

* Target low-performing months (**Feb, Jun, Sep**) with campaigns
* Apply discounts selectively on underperforming premium products

### 👥 Customer Retention

* Implement **tier-based loyalty program (Bronze → VIP)**
* Reward top 15% high-value customers

### 📦 Operational Improvements

* Reduce delivery time in high-delay categories
* Optimize logistics for international shipments

### ⭐ Customer Satisfaction

* Improve product descriptions and quality control
* Reduce return rate through better expectation setting

### 🌍 Market Strategy

* Focus marketing spend on high-performing regions
* Expand presence in underperforming geographies

---

## 🧠 Business Impact

This project demonstrates how raw e-commerce data can be transformed into a **decision intelligence system** that:

* Improves customer retention
* Optimizes product strategy
* Enhances operational efficiency
* Drives revenue growth

---

## 📌 Key Takeaway

A complete real-world analytics project combining **SQL + Power BI + DAX**, showcasing both **technical depth and business thinking**, aligned with stakeholder-driven decision making.

👩‍💻 Author : Amar
📧 [email ID: amarnitkkr814@gmail.com]
💼 [LinkedIn Profile URL: https://www.linkedin.com/in/amar0001/]



#  PySpark Data Pipeline Project (Phase 5 – Databricks)

##  Project Overview

This project focuses on building a complete data pipeline using PySpark on Databricks with a real-world e-commerce dataset. The goal is to process raw transactional data and transform it into meaningful insights for business analysis.

---

##  Dataset Description

The project uses the **Olist E-commerce Dataset**, which contains multiple related tables:

* Customers → customer details and location
* Orders → order-level information
* Order Items → product pricing and transactions
* Products → product categories

---

##  Project Goals

* Integrate multiple datasets
* Perform data transformation and analysis
* Apply advanced PySpark concepts
* Generate a final reporting dataset

---

## Implementation Details

### Data Loading

* Imported CSV files into Databricks
* Created DataFrames for each dataset
* Verified schema using PySpark

---

###  Data Integration

* Joined multiple tables using common keys:

  * `customer_id`
  * `order_id`
* Ensured consistency and correctness of joins

---

###  Data Analysis Tasks

####  Customer Analysis

* Calculated **Customer Lifetime Value (CLV)**
* Identified **Top Customers per City** using ranking

---

####  Sales Analysis

* Computed **daily sales**
* Calculated **running total** using window functions

---

####  Product Analysis

* Aggregated **total sales per product**
* Ranked products within each category using `DENSE_RANK`

---

####  Segmentation

* Categorized customers into:

  * Gold
  * Silver
  * Bronze
* Based on spending thresholds

---

###  Final Dataset

Created a consolidated reporting table with:

* customer_id
* customer_city
* total_spend
* segment
* total_orders

---

##  Key Skills Demonstrated

* PySpark DataFrame operations
* Joins and aggregations
* Window functions (rank, dense_rank, cumulative sum)
* Data transformation and feature engineering
* Real-world data pipeline design

---

##  Business Insights

* Identified high-value customers
* Analyzed customer distribution across segments
* Observed product performance across categories
* Tracked sales trends over time

---

##  Learning Outcomes

* Hands-on experience with real-world datasets
* Improved understanding of data pipelines
* Ability to translate raw data into business insights
* Practical exposure to Databricks environment

---




# Olist E-commerce SQL Analysis

### 1. Introduction

This project is an in-depth data analysis of the **Olist e-commerce dataset**, which contains real-world data from a Brazilian e-commerce platform. The primary goal is to use SQL to perform complex queries to answer key business questions related to customer behavior, sales performance, and logistics.

### 2. Dataset

The analysis is based on multiple relational tables provided in the Olist dataset, including:
* `olist_orders_dataset.csv`
* `olist_customers_dataset.csv`
* `olist_order_items_dataset.csv`
* And other related files.

These tables are joined and queried to extract meaningful insights from customer orders, products, and geographical data.

### 3. Business Questions & Analysis

The SQL queries were designed to answer a range of business questions, such as:
* What are the top-selling product categories?
* Which customers are most valuable (based on order count or total spending)?
* How does sales performance vary over time?
* Which regions have the highest number of orders?
* How long does it take for orders to be delivered on average?

### 4. Key Findings

* **[Example Finding]:** The analysis revealed that the "bed_bath_table" and "health_beauty" categories were the most popular among customers.
* **[Example Finding]:** The state of São Paulo consistently had the highest number of orders and sellers.
* **[Example Finding]:** A specific query helped identify a trend in order cancellations, providing a starting point for further investigation.

*(Note: You should replace these example findings with your actual discoveries from the analysis.)*

### 5. Technologies Used

* **SQL:** The core language used for all data querying and analysis.
* **[Database System]:** The database system where the tables were loaded and queries were executed (e.g., MySQL, PostgreSQL, SQLite).

### 6. How to Run the Queries

To replicate this analysis, you must first load the provided `.csv` files into a database of your choice. The SQL queries are available in the `ecommerce_olist_analysis.sql` file. You can run these queries against your database to see the results.

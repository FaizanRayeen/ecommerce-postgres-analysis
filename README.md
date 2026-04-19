E-Commerce Sales Analysis (PostgreSQL)

Project Overview
This project is an e-commerce sales analysis system built using PostgreSQL. It simulates a real-world online shopping platform and focuses on analyzing sales performance, customer behavior, product trends, and payment patterns using SQL.

The main objective is to convert raw transactional data into meaningful business insights.

---

Database Design

The project consists of five relational tables:

* customers: stores customer details such as name, city, and signup information
* products: contains product details including category and price
* orders: stores order-level information such as customer_id, order_date, and status
* order_items: contains product-level breakdown of each order with quantity and price
* payments: stores payment method and payment status details

---

Key Analysis Performed

Revenue Analysis

* Calculated total revenue and category-wise revenue
* Identified top-performing product categories

Customer Analysis

* Identified high-value customers based on total spending
* Analyzed customer order frequency and behavior

Product Performance

* Found best-selling products based on quantity and revenue
* Compared performance across different product categories

Payment Analysis

* Analyzed distribution of payment methods (UPI, Card, COD)
* Studied payment success, failure, and pending trends

Order Analysis

* Order status distribution (completed, pending, cancelled)
* Monthly order trends

---

SQL Concepts Used

* Basic SQL: SELECT, WHERE, ORDER BY, GROUP BY
* Joins: INNER JOIN across multiple tables
* Aggregate functions: SUM, COUNT, AVG
* Conditional logic: CASE WHEN
* Subqueries and CTE (WITH clause)
* Window functions: RANK, DENSE_RANK, LAG

---

Key Learnings

* Built a complete relational database system for e-commerce
* Learned structured data analysis using SQL
* Applied business logic to raw transactional data
* Used advanced SQL functions for deeper insights
* Improved ability to translate data into business decisions

---

Tools Used

PostgreSQL

---

Project Outcome

* Created a structured e-commerce analytics system
* Performed end-to-end data analysis using SQL
* Derived actionable business insights from raw data
* Strengthened SQL and analytical thinking skills

---


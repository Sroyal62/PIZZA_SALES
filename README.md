#**Pizza Sales Analysis Using SQL – Business Insights & Revenue Optimization**

..........................................................................

**Summary**

This project analyzes pizza sales data using SQL to extract meaningful business insights. The objective was to understand customer ordering behavior, revenue trends, peak sales hours, and product performance.

By performing SQL joins, aggregations, and grouping operations, this project demonstrates how raw transactional data can be transformed into actionable business intelligence.

..........................................................................

**Goals**

Calculate total number of orders placed

Compute total revenue generated

Identify highest-priced pizza

Determine the most commonly ordered pizza size

Find top 5 most ordered pizza types

Analyze category-wise pizza sales

Determine hourly distribution of orders

Derive insights for better business decision-making

..........................................................................


**Data Used**

The dataset consists of four relational tables:

orders.csv – Contains order date and time

order_details.csv – Contains quantity and pizza IDs

pizzas.csv – Contains price and pizza size

pizza_types.csv – Contains category and pizza names

These tables were joined using primary and foreign keys to perform analysis.

..........................................................................

**SQL Queries & Analysis**

Used COUNT() to calculate total orders

Used SUM(quantity * price) to compute total revenue

Used GROUP BY for category-wise and size-wise distribution

Applied ORDER BY and LIMIT to identify top-selling pizzas

Joined multiple tables to avoid data duplication

Analyzed order time to determine peak business hours

..........................................................................

**Importance of correct table joins**

Difference between:

Total Orders

Total Quantity Sold

Total Revenue

Avoiding aggregation errors

Using COUNT(DISTINCT) when required

Translating SQL output into business insights

Real-world data validation techniques

# PIZZA_SALES

Revenue must be calculated by multiplying price × quantity and joining the relevant tables:

SELECT SUM(od.quantity * p.price) AS total_revenue
FROM order_details od
JOIN pizzas p 
ON od.pizza_id = p.pizza_id;


🎯 Key Learning:

Always validate business logic before aggregation.

Understand the difference between:

Total Orders

Total Quantity Sold

Total Revenue

Ensure proper table joins to avoid duplication or incorrect totals.

Use COUNT(DISTINCT order_id) when calculating total orders.

some query:
Retrieve the total number of orders placed.
Calculate the total revenue generated from pizza sales.
Identify the highest-priced pizza.
Identify the most common pizza size ordered.
List the top 5 most ordered pizza types along with their quantities.

Join the necessary tables to find the total quantity of each pizza category ordered.
Determine the distribution of orders by hour of the day.
Join relevant tables to find the category-wise distribution of pizzas.
Group the orders by date and calculate the average number of pizzas ordered per day.
Determine the top 3 most ordered pizza types based on revenue.

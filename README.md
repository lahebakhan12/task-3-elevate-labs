# Task 3: SQL Data Analysis – Elevate Labs Internship

## Objective
Analyze an e-commerce database using SQL to extract meaningful business insights.

## Tools Used
- MySQL
- Git & GitHub

## Dataset
E-commerce database with `customers`, `products`, `orders`, and `order_items`.

## Key Analyses
1. **Customer Revenue Analysis** – Identified top revenue-generating customers.
2. **Product Performance Analysis** – Calculated total sales per product.
3. **City-wise Revenue Analysis** – Determined cities with highest revenue.
4. **Customer Lifetime Value View** – Reusable view for total revenue per customer.
5. **Advanced Product Revenue Query** – Products earning above average revenue.

## Optimizations
- Created index on `order_items.order_id` to improve JOIN query performance.

## Data Validation
- Verified that `orders.total_amount` matches sum of `order_items`. No inconsistencies found.

## Insights
- A small number of customers contribute the majority of revenue.
- Electronics category dominates sales revenue.
- Top cities: Delhi, Mumbai, Bangalore.
- Product-level revenue helps in inventory and pricing strategy.

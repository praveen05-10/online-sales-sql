# online-sales-sql
Objective: Identify loyal customers who have placed more than one order.
Query: Select customer_id, name, email, and the order count using COUNT(), grouped by customer_id.
HAVING Clause: Filters customers with more than one order (HAVING COUNT(order_id) > 1).
Use Case: Useful for designing loyalty programs by identifying repeat customers.
Optimization: Indexing on customer_id and considering performance for large datasets.

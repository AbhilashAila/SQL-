# SQL-
SQL Quires &amp; Scripts

--CREATE TABLE orders (
--    order_id INT PRIMARY KEY,
--    customer_id INT,
--    order_value DECIMAL(10,2)
--);

---- Insert sample records into the orders table
--INSERT INTO orders (order_id, customer_id, order_value)
--VALUES
--    (1, 1, 100.00),
--    (2, 1, 150.00),
--    (3, 2, 200.00),      
--    (4, 3, 250.00),
--    (5, 3, 300.00),
--    (6, 3, 350.00),
--    (7, 4, 400.00),     
--    (8, 5, 120.00),
--    (9, 5, 180.00);

-- Calculate the average order value per customer, excluding those with only one order

--select customer_id,
--           AVG(order_value) as Avg_order
--from orders
--             group by customer_id
--			 having COUNT(*)>1


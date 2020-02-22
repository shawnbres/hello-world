# hello-world
Hi
My name is Shawn

SELECT * FROM customers;

SELECT * FROM products;

SELECT * FROM vendors;

SELECT * FROM orders;

SELECT * FROM orderItems;

SELECT prod_name, prod_price 
FROM products 
WHERE prod_name 
LIKE '%bear';

SELECT Concat(vend_name, ' ', vend_country)
AS vend_title
FROM vendors
ORDER BY vend_name;

SELECT *, quantity*item_price 
AS Order_Total
FROM Orderitems;





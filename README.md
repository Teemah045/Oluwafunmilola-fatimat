<html>
   <head>
      </title>  
   </head>SELECT checkNumber, payment>
<SELECT orderDate, requiredDate, status>
<FROM orders>
<WHERE status = 'In Process'>
<ORDER BY orderDate DESC;>
<SELECT firstName, lastName, email
FROM employees
WHERE jobTitle = 'Sales Rep'
ORDER BY employeeNumber DESC;>
<SELECT *
FROM offices;>
<SELECT productName, quantityInStock
FROM products
ORDER BY buyPrice ASC
LIMIT 5;>



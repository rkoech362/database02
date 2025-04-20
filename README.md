select checknumber, paymentdate, amount from payments;
SELECT orderDate, requiredDate, status FROM orders WHERE status = 'In Process' ORDER BY orderDate DESC;
SELECT firstname, lastname, email from employees where jobtitle="sales rep" order by employeenumber DESC;
SELECT * from offices;
SELECT productName, quantityInStock FROM products ORDER BY buyPrice ASC LIMIT 5;

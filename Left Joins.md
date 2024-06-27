How It Works

**Tables:**

![Screenshot 2024-06-27 091243](https://github.com/Vijayananthperumal22/MY-SQL-Basics/assets/107705127/150262b6-cd81-48d0-8b27-55a6b37d7136)

**Code:**

```
SELECT Customers.CustomerName, Orders.OrderId
FROM Customers
LEFT JOIN Orders ON Customers.CustomerId = Orders.CustomerId;

```
**Result:**

![image](https://github.com/Vijayananthperumal22/MY-SQL-Basics/assets/107705127/23773230-453c-44a2-b191-27305c7dfb4c)

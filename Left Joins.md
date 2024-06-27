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

![Screenshot 2024-06-27 091243](https://github.com/Vijayananthperumal22/MY-SQL-Basics/assets/107705127/389d32cf-2661-4b1f-ac42-62e26e1a448d)

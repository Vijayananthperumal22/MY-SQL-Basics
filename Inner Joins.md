How It Works

**Table Structure:**
![Screenshot 2024-06-26 221757](https://github.com/Vijayananthperumal22/MY-SQL-Basics/assets/107705127/7c17a979-2a81-4fa1-866f-62dd51f6085e)

**Code:**
```
SELECT ProductId, ProductName, CategoryName
FROM Products
INNER JOIN Categories ON Products.CategoryId = Categories.CategoryId;
```

**Result:**
![26l2](https://github.com/Vijayananthperumal22/MY-SQL-Basics/assets/107705127/6b189c00-b04c-4665-8770-9728af85ae99)

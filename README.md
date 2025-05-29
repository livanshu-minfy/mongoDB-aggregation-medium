# mongoDB-aggregation-medium

i was assigned some tasks and asked to perform them and attach the screenshots this is a readme for easy tasks -->
**1. Total Quantity of Products by Supplier:**

- **Task:** Write an aggregation query to calculate the total `quantity` of products supplied by each `supplier.name`.
- **Hint:** Use `$group` on `supplier.name` and `$sum` on `quantity`.

![image](https://github.com/user-attachments/assets/e3fe166b-a4a4-4222-9eb5-5a18de5dce12)

**2. Average Price of Products per Tag:**

- **Task:** Write an aggregation query to find the average `price` of products associated with each `tag`. List the tag and its average price, sorted by average price in descending order.
- **Hint:** Use `$unwind` on `tags`, then `$group` on tags, and `$avg` on price. Finally, `$sort`.

![image](https://github.com/user-attachments/assets/128bcd82-107d-48a5-bcc2-1fef42d0cfad)

![image](https://github.com/user-attachments/assets/55049fd1-ec3b-45f1-98e5-f605655ced88)

![image](https://github.com/user-attachments/assets/9be12c35-2208-49eb-a965-87bc4463ca61)

**3. Products Added in February 2023:**

- **Task:** List the `name`, `category`, and the `date_added` (formatted as "YYYY-MM-DD") for products added in February 2023.
- **Hint:** Use `$match` with date range conditions on `date_added`. Then use `$project` with `$dateToString` to format the date.

![image](https://github.com/user-attachments/assets/019e6d1d-2329-4e4e-9be0-d73ee06a6eb6)

I have attached queries and their outputs in the screenshots and copy pasted the questions from the provided notion file.

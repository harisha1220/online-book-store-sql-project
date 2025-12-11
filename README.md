# Online Book Store — SQL Project
This project represents a complete SQL-based case study for an Online Book Store.
It includes database creation, table design, sample data, basic SQL queries, advanced analytical queries, and insights using MySQL.

This project is ideal for:

SQL beginners to practice real-world queries

Resume portfolio for analytics 

Interview preparation for SQL-heavy roles

Database Overview

The database contains 3 main tables:
1.Book Table

| Column         | Description             |
| -------------- | ----------------------- |
| book_id        | Unique ID               |
| title          | Book title              |
| author         | Name of the author      |
| genre          | Fiction / Fantasy / etc |
| price          | Book price              |
| stock          | Current available stock |
| published_year | Publication year        |

2.Customer Table

| Column      | Description        |
| ----------- | ------------------ |
| customer_id | Unique customer ID |
| name        | Customer name      |
| city        | City               |
| country     | Country            |

3.Order Table

| Column       | Description      |
| ------------ | ---------------- |
| order_id     | Unique order ID  |
| book_id      | FK → books       |
| customer_id  | FK → customers   |
| quantity     | Quantity ordered |
| total_amount | Price × quantity |
| order_date   | Date of purchase |

**Basic SQL Queries:**

1.The project includes basic SQL operations such as:

2.Retrieving books by genre

3.Finding recently published books

4.Filtering orders by date

5.Aggregation queries (SUM, COUNT, AVG)

6.Sorting and limiting results

**Advanced SQL Queries**

Advanced analytical queries include:

1.Most frequently ordered book

2.Total books sold per genre

3.Customers with 2+ orders

4.Revenue calculations

5.Stock remaining after orders

6.Top spending customer

# Task 4: SQL for Data Analysis

## 📌 Objective
Analyze structured data using SQL queries. The focus is on retrieving, filtering, joining, aggregating, and optimizing data using standard SQL commands.

---

## 🧰 Tools Used
- **DB Browser for SQLite** (Desktop SQL client)
- **Sakila Sample Database** (DVD rental data)
- Queries written and tested using SQLite engine

---

## 🗃️ Database Used
**Sakila DB** — a sample movie rental database containing tables like:
- `customer`
- `rental`
- `payment`
- `film`
- `staff`
- `inventory`
- `category`

---

## 📊 SQL Queries Performed

| # | Query Description |
|--|--------------------|
| 1 | Show all customers |
| 2 | Show all rental records |
| 3 | Total number of rentals per film (with film title) |
| 4 | Total payment received per customer |
| 5 | List all films in the "Comedy" category |
| 6 | Total number of customers per city |
| 7 | Show all payments over $10 |
| 8 | Total payments collected by each staff member |
| 9 | Created a view `top_customers` (paid > $100) |
| 10 | Created an index on `rental.rental_date` for optimization |

---

## 📁 Files Included

- `task4_queries.sql` → All 10 SQL queries
- `query_outputs.pdf` or `/screenshots` folder → Output of each query (optional but recommended)
- `sakila_er_diagram.png` (optional) → Entity relationship diagram of the database (if included)
- `README.md` → This file

---

## 🧠 Key Insights

- Top 10 most-rented films identified
- High-value customers highlighted via `top_customers` view
- Staff-wise revenue breakdown helps identify top performers
- Category-wise film search (e.g., Comedy)
- Indexing applied for performance tuning

---

# Task 3: SQL for Data Analysis

## 📌 Objective
To extract and analyze customer support data using SQL queries.

## 🔧 Tools Used
- Google Colab (Python, Pandas, SQLite)
- SQLite for query execution
- GitHub for submission

## 📁 Dataset
Customer_support_data.csv

## ✅ What I Did
- Used SELECT, WHERE, ORDER BY, GROUP BY
- Performed INNER JOIN using agent data
- Wrote subqueries and CTEs
- Used aggregate functions like AVG and COUNT
- Created Views (optional in SQLite)
- Simulated indexing and performance
- Categorized CSAT score with CASE

## ❓ Interview Questions Answered
1. **WHERE vs HAVING**: WHERE filters rows before grouping; HAVING filters after GROUP BY.
2. **Types of JOINs**: INNER, LEFT, RIGHT, FULL OUTER.
3. **Avg Revenue/User**: `SELECT AVG(revenue) FROM users`
4. **Subqueries**: Nested queries inside `SELECT`, `FROM`, or `WHERE`.
5. **Optimize SQL**: Use indexes, avoid `SELECT *`, filter early, use EXPLAIN.
6. **View in SQL**: A saved SQL query, like a virtual table.
7. **Handle NULLs**: Use `IS NULL`, `COALESCE()`, or `IFNULL()`.

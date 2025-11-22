# 📊 Task 6 – Sales Trend Analysis Using SQL
📌 Objective

The goal of this task is to analyze sales trends over time using SQL aggregation functions such as SUM, COUNT, GROUP BY, ORDER BY, and LIMIT.

🛠 Tools Used

SQLite (SQLiteOnline.com)

SQL Queries

📁 Dataset

A sample sales dataset containing:

order_id

order_date

product_id

amount

(Used for monthly trend analysis.)

🔍 Steps Performed

Loaded the sales dataset into a SQL environment.

Extracted year and month from the order_date column.

Calculated total monthly revenue using SUM(amount).

Calculated order volume using COUNT(DISTINCT order_id).

Sorted results using ORDER BY year, month.

Identified best-performing months using LIMIT with highest revenue.

📈 Output Summary

✔ Monthly revenue trend generated
✔ Monthly order count calculated
✔ Top revenue months identified
✔ Final summarized table exported

📄 Deliverables

SQL script (queries.sql)

Screenshot(s) of query results

README.md

✅ Outcome

This task helped understand how SQL aggregations can be applied to real business datasets to reveal trends, patterns, and performance insights.

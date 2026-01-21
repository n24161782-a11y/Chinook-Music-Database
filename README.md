# SQL Task 3 – Chinook Music Database

## Project Overview
This project analyzes the Chinook music store database using a single SQL query.  
The query summarizes sales by genre, demonstrating filtering, aggregation, grouping, joins, and sorting.

---

## Platform
- SQLite Online (https://sqliteonline.com)

---

## Tables Used
- Track  
- Genre  
- InvoiceLine

---

## Query Description
The SQL query:
- Filters tracks with price ≥ 0.99  
- Joins Track, Genre, and InvoiceLine tables  
- Calculates total tracks, total units sold, total revenue, and average price  
- Groups by genre  
- Filters genres with revenue > 100  
- Orders by total revenue descending

---

## Output
- `chinook_sales_summary.csv` – Aggregated sales data by genre  

---

## Repository Structure

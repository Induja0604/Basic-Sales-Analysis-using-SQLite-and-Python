# Basic Sales Analysis using SQLite and Python

##  Project Overview
This project demonstrates how to:
- Create a SQLite database using Python
- Insert sales records
- Run SQL queries using GROUP BY and SUM
- Load results into Pandas
- Visualize revenue using Matplotlib

##  Tools Used
- Python
- SQLite (sqlite3)
- Pandas
- Matplotlib
- Jupyter Notebook

##  SQL Query Used
SELECT 
    product,
    SUM(quantity) AS total_qty,
    SUM(quantity * price) AS revenue
FROM sales
GROUP BY product;

##  Output
- Total quantity sold per product
- Total revenue per product
- Bar chart visualization

##  Learning Outcome
- Writing SQL inside Python
- Data aggregation using GROUP BY
- Data visualization using matplotlib


--Developed by
Induja

# Task 7: Sales Summary using SQLite and Python

This project is part of a Data Analyst Internship Task. The objective is to extract and visualize basic sales information using **SQLite**, **Python**, and data visualization tools.

---

## 📁 Project Overview

- Connect to an SQLite database using Python
- Run SQL queries to calculate:
  - Total quantity sold per product
  - Total revenue per product
- Load results into a pandas DataFrame
- Visualize the revenue data using a bar chart via `matplotlib`

---

## 🧪 Dataset Description

This project uses a **sample dataset** stored in an SQLite database (`sales_data.db`) with a single table named `sales`.  
The table includes the following fields:

| Field     | Description             |
|-----------|--------------------------|
| product   | Name of the product      |
| quantity  | Units sold               |
| price     | Unit price of the product|

---

## ✅ What I Did in the Dataset

- Created a small SQLite database (`sales_data.db`) containing sample sales records
- Connected to the database using Python’s built-in `sqlite3` module
- Executed a SQL query to compute:
  - Total quantity sold per product using `SUM(quantity)`
  - Total revenue per product using `SUM(quantity * price)`
- Grouped results by product using SQL’s `GROUP BY` clause
- Loaded the query result into a pandas DataFrame
- Printed the DataFrame for summary view
- Plotted a bar chart to visualize total revenue per product using `matplotlib`

---

## 🛠 Tools Used

- Python 
- SQLite (`sqlite3`)
- pandas
- matplotlib
- Jupyter 
---

## 💻 How to Run

1. Ensure Python is installed with required packages:
    ```bash
    pip install pandas matplotlib
    ```

2. Run the Jupyter notebook:
    ```bash
    jupyter notebook "Sample Sales_data.ipynb"
    ```

---

## 📊 Output

- **Printed Summary Table**: Shows each product with total quantity sold and total revenue
- **Bar Chart**: Visualizes revenue generated per product

---

## 📌 Notes

- This task uses a **sample dataset** created for demonstration purposes.
- You can customize the `sales` table and extend the analysis further.

---

## Author -- Sahil Singh
- Date of Submission = 1-05-2025

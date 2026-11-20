# University Database SQL Queries (SQL Server & Jupyter Notebook)

This repository contains a collection of analytical and operational **SQL Server** queries executed directly inside a **Jupyter Notebook** environment using `ipython-sql` and `pyodbc`. The project was completed as part of the SQL training program at the **Information Technology Institute (ITI) - Sohag Branch**.

## 📌 Project Overview
The notebook demonstrates querying and managing a relational **University Management Database** (`iT`), covering student records, departments, courses, professors, administrative staff, and research projects.

## 🛠️ Tools & Technologies
* **Database:** Microsoft SQL Server (T-SQL)
* **Environment:** Jupyter Notebook / Anaconda
* **Python Libraries:** `ipython-sql`, `SQLAlchemy`, `pyodbc`

## 📂 Key SQL Concepts Covered
1. **Aggregate Functions & Grouping:**
   * Calculating total students per department and research project.
   * Analyzing average, minimum, and maximum student GPAs across departments and enrollment years.
2. **Multi-Table Joins (`INNER JOIN` & `LEFT JOIN`):**
   * Retrieving student course enrollments, department faculty assignments (including departments without assigned professors), and research project involvements.
3. **Set Operations (`UNION`):**
   * Combining records across students, professors, and administrative staff into unified directories with conditional filtering.
4. **Filtering, Pattern Matching & Conditional Logic:**
   * Using `LIKE`, `IN`, `BETWEEN`, `TOP`, and `CASE` statements for GPA classification and targeted data retrieval.
5. **Database Views (`CREATE OR ALTER VIEW`):**
   * Building reusable virtual tables (`dep_12`, `dep_cour`, `st_cour`, `smg`) to simplify complex multi-table queries.
6. **Stored Procedures (`CREATE OR ALTER PROCEDURE`):**
   * Creating parameterized stored procedures (`GET_TOP`) to dynamically filter top-performing students based on a minimum GPA threshold.

# Student Performance SQL Analysis

##  Project Overview

This project analyzes student academic performance using **MySQL**. The analysis focuses on student marks across different subjects and uses SQL queries to identify performance trends, averages, highest and lowest scores, and top-performing students.

##  Objectives

* Analyze student performance across subjects
* Calculate average, highest, and lowest marks
* Identify top-performing students
* Perform subject-wise performance analysis
* Practice SQL data analysis techniques

##  Tools & Technologies

* MySQL
* MySQL Workbench
* SQL

##  Database Structure

The project contains three tables:

### 1. Students

Stores student information.

* `student_id`
* `student_name`
* `gender`
* `age`

### 2. Subjects

Stores subject information.

* `subject_id`
* `subject_name`

### 3. Marks

Stores marks obtained by students.

* `mark_id`
* `student_id`
* `subject_id`
* `marks`

##  SQL Concepts Used

* `CREATE DATABASE`
* `CREATE TABLE`
* `INSERT`
* `SELECT`
* `JOIN`
* `GROUP BY`
* `ORDER BY`
* Aggregate Functions:

  * `AVG()`
  * `MAX()`
  * `MIN()`
  * `COUNT()`
* Subqueries
* `CASE WHEN`

##  Analysis Performed

The project includes analysis such as:

1. Combining student, subject, and marks data using `JOIN`.
2. Calculating subject-wise average marks using `GROUP BY` and `AVG()`.
3. Ranking subjects according to average performance using `ORDER BY`.
4. Finding highest, lowest, and average marks using aggregate functions.
5. Identifying students whose marks are above the overall average using a subquery.
6. Finding the highest-scoring student(s).
7. Finding the highest marks in each subject.
8. Performing Pass/Fail analysis using `CASE WHEN`.
9. Creating a student performance summary using multiple SQL concepts.

##  Project Files

* `student_analysis.sql` — Contains the complete SQL database creation, data insertion, and analysis queries.
* `README.md` — Project documentation.

##  Key Learning

Through this project, I practiced writing SQL queries for data analysis and learned how to combine multiple tables, summarize data using aggregate functions, filter results, and use subqueries for advanced analysis.

##  Author

**Kanak Varshney**

BCA | SQL | Python | Power BI

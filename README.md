# MySQL Learning Project: Clauses and Aggregate Functions

## 📌 Project Overview

This project demonstrates the practical application of MySQL
for relational database creation, data manipulation, data filtering,
sorting, grouping, and data analysis.

A sample database named `bioinfo` is used to practice SQL queries
on a `student` table. The project covers fundamental SQL clauses,
aggregate functions, and advanced query combinations.

The repository is organized to support hands-on learning,
query practice, and future reference.

## 🎯 Objectives

- Understand relational database creation in MySQL.
- Create tables with appropriate data types and constraints.
- Insert and retrieve records using SQL queries.
- Filter records using WHERE and logical operators.
- Sort and limit query results.
- Group records using GROUP BY.
- Perform calculations using aggregate functions.
- Filter aggregated results using HAVING.
- Combine multiple SQL clauses in practical queries.

## 🛠️ Technologies Used

- MySQL 8.4
- SQL
- Ubuntu Linux
- Git and GitHub

## 🗄️ Database Structure

Database Name: `bioinfo`

Table Name: `student`

The student table contains the following columns:

| Column | Data Type | Description |
|---|---|---|
| student_id | INT | Unique student identifier |
| first_name | VARCHAR(30) | Student's first name |
| last_name | VARCHAR(30) | Student's last name |
| age | INT | Student's age |
| gender | VARCHAR(10) | Student's gender |
| department | VARCHAR(50) | Academic department |
| marks | DECIMAL(5,2) | Student's marks |
| email | VARCHAR(100) | Student's email address |
| city | VARCHAR(30) | Student's city |

## 📚 Topics Covered

### 1. Database and Table Creation
- CREATE DATABASE
- USE
- CREATE TABLE
- INSERT INTO

### 2. Data Retrieval
- SELECT
- DISTINCT

### 3. Data Filtering
- WHERE
- Comparison operators
- AND, OR, NOT
- BETWEEN
- IN
- LIKE

### 4. Sorting and Limiting
- ORDER BY
- ASC and DESC
- LIMIT
- OFFSET

### 5. Grouping and Aggregation
- GROUP BY
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()

### 6. Group Filtering and Advanced Queries
- HAVING
- WHERE vs HAVING
- Aliases using AS
- DISTINCT with aggregate functions
- Combining WHERE, GROUP BY, HAVING,
  ORDER BY, and LIMIT

## 🚀 Getting Started

### Prerequisites

Install MySQL Server and ensure that the service is running.

Check the MySQL version:

```bash
mysql --version

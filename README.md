# SQL Practice Solutions

A collection of MySQL problems solved while strengthening my SQL
problem-solving and analytical skills.

## 🎯 Objective

The goal of this repository is to practice SQL concepts commonly
used in Data Analyst and Business Analyst roles.

## 🛠️ Tools

- MySQL
- Git
- GitHub

## 📚 Topics Covered

| Topic 
|---|---:|
| SQL Basics
| Aggregation
| String Functions
| Date Functions
| Joins
| Subqueries
| CTEs
| Window Functions
| Advanced SQL
| Interview Problems

## 📈 Skills Demonstrated

- Data filtering
- Aggregation
- Joins
- Subqueries
- CTEs
- Window functions
- Ranking
- Date analysis
- String manipulation
- Conditional logic
- Analytical problem solving

## 📂 Repository Structure

01_Basics/
02_Aggregation/
03_String_Functions/
04_Date_Functions/
05_Joins/
06_Subqueries/
07_CTE/
08_Window_Functions/
09_Advanced_SQL/
10_Interview_Problems/

## 💡 Sample Problems

### Second Highest Salary

```sql
SELECT MAX(salary)
FROM employees
WHERE salary < (
    SELECT MAX(salary)
    FROM employees
);

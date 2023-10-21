# SQL Project - Business Analysis

A comprehensive analysis of business data using SQL queries to solve critical problem statements.

## Overview


## Deliverables

The project's deliverables include the following:

- **SQL Query File**: Contains the SQL queries used to generate data for solving each problem statement.
- **Presentation Slides**: A PowerPoint or Google Slides presentation summarizing the key findings, along with data representation in chart format.

## Problem Statements

### 1. Top 10 Highest Selling Products
**Problem Statement:** Determine the top 10 highest selling products in the database using the `salesorderdetail` table and `LineTotal` as sales. Create a Pie chart to visualize this information.

**Explanation of Code:** 

```sql
-- SQL Query for Problem Statement 1
SELECT TOP 10 ProductName, SUM(LineTotal) AS TotalSales
FROM salesorderdetail
GROUP BY ProductName
ORDER BY TotalSales DESC;
```

## Presentation and Findings

![Table Output of Data](Table_Question_1.png)


![Pie Chart of Data](PIE_Chart_Question_1.png)

# SQL Project - Business Analysis

A comprehensive analysis of business data using SQL queries to solve critical problem statements.

## Table of Contents
- [Overview](#overview)
- [Deliverables](#Deliverables)
- [Problem Statements](#Problem-Statements)
- [Presentation and Findings](#Presentation-and-Findings)

## Overview

Here is the sql to calculate the provided problem and the data output screenshots.


## Deliverables

The project's deliverables include the following:

- **SQL Query File**: Contains the SQL queries used to generate data for solving each problem statement.
- **OUTPUT**: OUTPUT TABLE.
- **PIE CHART**: PIE CHART.

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

THE TABLE OF OUTPUT DATA

![Table Output of Data](Table_Question_1.png)

THE PIE CHART CREATED WITH OUTPUT DATA

![Pie Chart of Data](PIE_Chart_Question_1.png)

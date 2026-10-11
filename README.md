# E-Commerce-Customer-Churn-Analysis

E-Commerce Customer Churn Analysis using MySQL for data cleaning, transformation, and customer behavior analysis.

## Project Overview
This project analyzes e-commerce customer data to understand customer churn, purchasing behavior, satisfaction levels, and payment preferences.

## Project Objectives
- Clean and prepare customer data for analysis.
- Identify active and churned customers.
- Analyze customer satisfaction, complaints, and purchasing patterns.
- Explore factors associated with customer churn.

## Tools Used
- MySQL
- MySQL Workbench

## Project Steps

### 1. Data Cleaning
- Handled missing values using mean and mode imputation.
- Removed outliers from warehouse-to-home distance.
- Standardized inconsistent values in login devices, order categories, and payment modes.

### 2. Data Transformation
- Renamed columns for better consistency.
- Created ComplaintReceived and ChurnStatus columns.
- Removed unnecessary original columns.

### 3. Data Exploration and Analysis
- Analyzed active and churned customers.
- Examined customer tenure, cashback, and complaints.
- Analyzed payment preferences and coupon usage.
- Explored customer satisfaction and order patterns.
- Compared churn status across warehouse distance categories.
- Used SQL joins to analyze customer returns.

## SQL Concepts Used
- SELECT, WHERE, DISTINCT
- GROUP BY, ORDER BY, HAVING
- COUNT, SUM, AVG, MAX
- CASE Statements
- Subqueries
- INNER JOIN

## Conclusion
This project demonstrates the application of SQL for data cleaning, transformation, and customer churn analysis to support data-driven business decisions.

# Bank Churn Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)

### Project Overview

This data analysis project explores the churn rate of a fictional bank using SQL and Power BI. The goal was to identify patterns and key drivers behind customer attrition. I analyzed variables such as customer satisfaction, credit score, complaints, and active membership to uncover insights into churn behavior.

To simulate a real world business environment, I used ChatGPT to act as a Product Manager and as a Stakeholder to define business goals and KPIs. This project was completed entirely without following any YouTube tutorials, allowing me to demonstrate my independent problem solving skills and ability to manage a data project from start to finish. It serves as a showcase of my growing skill set as an aspiring data analyst.

Put dashboard picture here

### Data Sources

Bank Churn Data: The main dataset used in this project is the "Customer-Churn-Records.xlsx" file, which includes detailed records of customers that stayed and left the bank. 

### Tools

Microsoft Excel – Initial data inspection, formatting, and column cleanup of the .xlsx dataset

SQL Server Management Studio (SSMS) – Data cleaning, transformation, and exploratory analysis

Power BI – Interactive dashboard creation, KPI tracking, and data visualization

ChatGPT – Simulated stakeholder collaboration to define KPIs and business goals


Absolutely — you've earned some rest, and I’ve got you covered. Based on everything we've done in this project, here’s a clear and professional **Data Cleaning/Preparation** section you can paste into your write-up:

### Data Cleaning / Preparation

During the data preparation phase, I performed several steps to ensure the dataset was clean, consistent, and ready for analysis:

1. Loaded the original `.xlsx` file into Microsoft Excel to inspect the data and clean unnecessary columns such as `RowNumber` and `Surname`.
2. Verified there were no duplicate rows using Excel and SQL queries in SQL Server Management Studio.
3. Created calculated columns such as `ChurnFlag` and `ComplaintLabel` using SQL `CASE` statements in PowerBI for better readability.
4. Standardized and validated data types for each column to ensure numerical fields like `Balance` and `CreditScore` were properly typed.
6. Loaded the cleaned dataset into Power BI for analysis and visualization.

### Exploratory Data Analysis

EDA involved exploring the bank churn data to answer key questions, such as:

KPI's Requirement
- Total Customers
- Churn Rate
- Average Tenure
- Average Balance
- Product Holding Ration
- Active Member Churn Rate
- Complain Rate
- Average Satisfaction Score
- Average Points by Card Type
- Churn by Geography

### Data Analysis

These are the queries I used to analyze the data set


















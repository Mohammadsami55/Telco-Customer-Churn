# Telco-Customer-Churn

📊 Telco Customer Churn Analysis (Tableau)
📌 Project Overview

This project focuses on analyzing customer churn using the Telco Customer Churn dataset.
The main goal is to understand why customers leave the service and identify key factors that influence churn using data visualization in Tableau.

🎯 Objective

To explore and understand customer data

To identify churn patterns using visual analytics

To help businesses improve customer retention strategies

🗂 Dataset Description

Dataset Name: Telco Customer Churn

Format: CSV

Rows: Each row represents one customer

Target Column: Churn (Yes / No)

Key Columns:

Customer Info: gender, SeniorCitizen, Partner, Dependents

Account Info: tenure, Contract, PaymentMethod

Services: InternetService, OnlineSecurity, TechSupport, StreamingTV

Billing: MonthlyCharges, TotalCharges

Churn: Indicates whether the customer left the company

🧹 Data Cleaning (Performed in Tableau)

The following data cleaning steps were applied:

Corrected data types for numeric fields

Handled missing values in TotalCharges (replaced with 0 for zero-tenure customers)

Removed inconsistencies in categorical values

Created Tenure Bins for better analysis

Verified uniqueness of customer records

📊 Visualizations Created

The following visualizations were developed using Tableau:

Churn Distribution – Customers who stayed vs left

Churn by Tenure Bin – Identifies early churn customers

Churn by Contract Type – Month-to-month vs long-term contracts

Churn vs Monthly Charges – Impact of billing on churn

Radial (Donut) Chart – Churn proportion visualization

Dashboard – Combined view of key churn insights

🔍 Key Insights

Customers with low tenure (0–12 months) have the highest churn

Month-to-month contracts show significantly higher churn

Higher monthly charges increase churn probability

Customers without online security or tech support are more likely to churn

🛠 Tools & Technologies

Tableau Desktop – Data visualization & dashboard creation

CSV Dataset – Data source

GitHub – Project hosting and version control

📁 Project Files

Telco-Customer-Churn.csv – Dataset

new project 1.twb – Tableau Workbook

README.md – Project documentation

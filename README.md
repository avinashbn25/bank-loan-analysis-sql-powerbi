# bank-loan-analysis-sql-powerbi
End-to-end bank loan portfolio analysis using SQL and Power BI. Extracted KPIs, analyzed funding and repayments, segmented risk (Good vs Bad loans), and built interactive dashboards to uncover trends across time, geography, and borrower demographics.
Project Overview

This project presents a comprehensive analysis of a bank’s loan portfolio using SQL for data extraction and transformation, and Power BI for visualization and reporting. The goal is to generate actionable insights into loan performance, borrower behavior, and financial risk.

🎯 Objectives

Provide a complete view of loan portfolio performance

Analyze loan applications, funding, and repayment trends

Evaluate financial metrics such as:

Total Funded Amount

Total Amount Received

Average Interest Rate

Debt-to-Income (DTI) Ratio

Loan Status Distribution

Support strategic decision-making using data insights

🗂️ Data Source

The dataset is stored in SQL Server and includes:

Loan amount and funded amount

Issue date and loan term

Interest rate and DTI ratio

Loan status (Fully Paid, Current, Charged Off)

Borrower employment length, purpose, and home ownership

⚙️ Methodology
1️⃣ Database & Data Preparation

Created relational database in SQL Server

Imported and structured loan dataset

Performed data validation and cleaning

2️⃣ KPI Development (SQL)

Total & Month-to-Date (MTD) applications

Previous Month-to-Date (PMTD) comparison

Total funded vs total received amount

Average interest rate & DTI

Loan status breakdown

3️⃣ Risk Segmentation

Classified loans as Good or Bad

Analyzed funded and received amounts by risk category

Evaluated overall portfolio risk

4️⃣ Multi-Dimensional Analysis

Breakdowns by:

Month

State

Loan Term

Employment Length

Loan Purpose

Home Ownership

5️⃣ Power BI Dashboard

Built interactive dashboards

Validated SQL results with visual outputs

Enabled dynamic filtering for deeper insights

📈 Key Insights

Growth trends using MTD vs PMTD comparison

Liquidity insights from funded vs received amounts

Risk profiling using loan status segmentation

Geographic and purpose-based lending patterns

🛠️ Tools & Technologies

SQL Server Management Studio (SSMS)

Power BI

🚀 Future Enhancements

Predictive modeling for loan default forecasting

Advanced risk scoring

Time-series analysis for loan performance

Deeper borrower demographic

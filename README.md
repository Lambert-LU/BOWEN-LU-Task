# FinServe Automated Reporting

## Overview
This project focuses on improving the financial and risk reporting process in a financial services company.

The goal is to replace manual Excel-based reporting with an automated solution.

## Solution
An automated reporting system was implemented using Python.

- Models are trained on previous data (data_last)
- Applied to new data (data_now)
- A quarterly report is generated automatically

## Models
- Ordered Logistic Regression (risk level)
- Logistic Regression (churn)

## Automation
The reporting process is implemented as a reusable function (OOP), allowing reports to be generated with a single function call.

## Output
The system produces a simple quarterly report with key metrics such as:
- total customers
- risk distribution
- churn rate

## Future Improvements
- Use SQL for data storage
- Support multi-period (panel data) analysis
- Add dashboards (Power BI / Tableau)

## Author
BOWEN LU

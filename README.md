# Financial Fraud Detection Analysis Project

## Project Overview
This project aims to analyze financial transaction data to identify fraud patterns, enabling a bank to reduce financial losses, comply with regulatory requirements, and support decision-making for risk management. The analysis uses R, RStudio, Tableau, BigQuery, and Google Spreadsheet, with progress tracked on GitHub and Kaggle.

## Problem Statement
How can we identify fraud patterns in transaction data to help the bank's risk management team reduce financial losses, ensure compliance with regulations (e.g., AML, GDPR), and provide actionable insights for decision-makers?

## SMART Goals
- **Specific**: Use Kaggle’s "Credit Card Fraud Detection" dataset to analyze transaction patterns (e.g., amount, time, frequency) and build a logistic regression model to detect fraudulent transactions.
- **Measurable**: Achieve a model recall rate of ≥90% and a false positive rate of ≤10%, with an estimated fraud loss reduction of 10% (approx. $500,000 based on historical data).
- **Achievable**: Leverage beginner-friendly tools (R’s tidyverse and caret, Tableau) to perform data cleaning, exploratory data analysis (EDA), and modeling within 4 weeks.
- **Relevant**: Provide insights on high-risk transactions, compliance reports, and ROI analysis to meet the needs of the risk management team, compliance department, and executives.
- **Time-bound**: Complete analysis and deliver a report within 4 weeks (20 hours, 1 hour/day, 5 days/week).

## Stakeholders
- **Risk Management Team**: Needs high-recall fraud detection and low false positives to minimize customer complaints.
- **Compliance Department**: Requires anonymized data and documented processes to meet regulatory standards.
- **Executives**: Seeks cost-benefit analysis and insights into emerging fraud trends for strategic planning.

## Repository Structure
- `data/`: Contains subfolders for project assets:
  - `scripts/`: R scripts for data processing and modeling.
  - `notebooks/`: R Markdown or Jupyter notebooks for analysis.
  - `outputs/`: Exported charts, tables, and model results.
  - `docs/`: Project documentation and reports.
  - `tableau/`: Tableau workbooks and dashboards.
  - `google-sheets/`: Links to Google Spreadsheets for metadata and tracking.
- `README.md`: Project overview and goals.
- `.gitignore`: Excludes temporary files and sensitive data.

## Next Steps
- Download Kaggle’s "Credit Card Fraud Detection" dataset and store it in `data/`.
- Perform initial data exploration using R and BigQuery.
- Document progress in Google Spreadsheet and Kaggle notebooks.

# VerifyIQ — Customer Risk & Transaction Monitoring

A portfolio project inspired by real-world banking compliance analytics workflows.

This project simulates how financial institutions monitor customer risk profiles, suspicious transaction activity, and compliance exposure using SQL-based analysis.

It demonstrates practical risk analytics, fraud detection logic, and transaction monitoring concepts commonly used in banking and financial compliance environments.

---

## Project Overview

VerifyIQ is a customer risk monitoring and transaction analytics project built using synthetic KYC and transaction data.

The objective of this project is to analyze customer behavior, identify risky entities, and detect suspicious transaction patterns through structured SQL analysis.

This project focuses on identifying:

- High-risk customers
- Politically Exposed Persons (PEPs)
- Sanctioned customers
- FATF / OFAC risk exposure
- Suspicious transaction behavior
- High-value transaction anomalies

---

## Business Problem

Banks and financial institutions must continuously monitor customer activity to detect suspicious behavior, fraud risks, and compliance violations.

This project helps answer important business questions such as:

- Which customers are classified as high risk?
- How many PEP customers exist?
- Are sanctioned entities present in the customer base?
- Which customers moved the highest transaction volumes?
- What suspicious transaction patterns are visible?

---

## Tech Stack

- PostgreSQL
- SQL
- Excel
- Power Query
- CSV Data Cleaning

---

## Project Structure

```text
VerifyIQ-Customer-Risk-Monitoring
│
├── data
│   ├── clients_clean.csv
│   └── transactions_with_fatf_ofac.csv
│
├── sql
│   └── queries.sql
│
├── screenshots
│   ├── total_clients.png
│   ├── total_transactions.png
│   ├── top_customers_analysis.png
│   ├── high_risk_analysis.png
│   ├── pep_customer_analysis.png
│   └── suspicious_high_risk.png
│
└── README.md
```

---

## Key Analysis Performed

### Customer Risk Analysis
- High-risk customer identification
- Customer segmentation analysis
- PEP customer analysis
- Sanctions monitoring
- FATF / OFAC exposure analysis

### Transaction Monitoring
- Total transaction volume analysis
- Transaction value analysis
- Top customer transaction analysis
- Suspicious activity detection
- High-value transaction monitoring

---

## SQL Analysis Highlights

The project includes SQL analysis covering:

- Total customer count
- Total transaction count
- Customer type distribution
- Risk category analysis
- PEP customer monitoring
- Sanctioned customer analysis
- FATF / OFAC exposure checks
- Top transaction customers
- Suspicious structuring pattern detection
- High-risk customer investigation

---

## Project Screenshots

### Total Customers Analysis
![Total Customers](./screenshots/total_clients.png)

### Total Transactions Analysis
![Total Transactions](./screenshots/total_transactions.png)

### Top Customer Analysis
![Top Customers](./screenshots/top_customers_analysis.png)

### High Risk Analysis
![High Risk](./screenshots/high_risk_analysis.png)

---

## Skills Demonstrated

- SQL Query Writing
- PostgreSQL
- Data Cleaning
- Risk Analysis
- Fraud Detection
- Business Analysis
- Transaction Monitoring

---

## Relevant Roles

This project is relevant for:

- Data Analyst
- Risk Analyst
- AML Analyst
- Fraud Analyst

---

## Future Enhancements

Planned next step:

- Interactive Power BI Dashboard
- KPI Monitoring Dashboard
- Risk Visualization
- Fraud Trend Analysis

---

## Note

This project uses synthetic data for learning and portfolio purposes.

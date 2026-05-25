# VerifyIQ — Customer Risk & Transaction Monitoring

A portfolio project inspired by real-world banking compliance analytics workflows.

This project simulates how financial institutions monitor customer risk profiles, suspicious transaction activity, and compliance exposure using SQL-based analysis.

It demonstrates practical risk analytics, fraud detection logic, and transaction monitoring concepts commonly used in banking and financial compliance environments.

---

## Project Overview

VerifyIQ is a customer risk monitoring and transaction analytics project built using synthetic KYC and transaction data.

The objective of this project is to analyze customer behavior, identify risky customers, and detect suspicious transaction patterns through SQL analysis.

This project focuses on:

- High-risk customer identification
- PEP (Politically Exposed Person) analysis
- Sanctioned customer monitoring
- FATF / OFAC risk exposure analysis
- Suspicious transaction detection
- High-value customer transaction analysis

---

## Business Problem

Banks and financial institutions must continuously monitor customer activity to detect suspicious behavior, fraud risks, and compliance violations.

This project helps answer business questions such as:

- Which customers are classified as high risk?
- How many PEP customers exist?
- Are sanctioned entities present?
- Which customers moved the highest transaction amounts?
- What suspicious transaction patterns exist?

---

## Tech Stack

- PostgreSQL
- SQL
- Excel
- Power Query

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
│   └── top_customers_analysis.png
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
- Total transaction amount analysis
- Top customer transaction analysis
- Suspicious activity detection
- Risk-based customer monitoring

---

## SQL Analysis Highlights

The project includes analysis for:

- Total customer count
- Total transaction count
- Customer type distribution
- Risk category analysis
- PEP customer monitoring
- Sanctioned customer analysis
- FATF / OFAC exposure checks
- Top transaction customers
- Suspicious transaction detection
- High-risk customer investigation

---

## Project Screenshots

### Total Customers Analysis
![Total Customers](./screenshots/total_clients.png)

### Total Transactions Analysis
![Total Transactions](./screenshots/total_transactions.png)

### Top Customer Transaction Analysis
![Top Customers](./screenshots/top_customers_analysis.png)

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

Next planned phase:

- Interactive Power BI Dashboard
- KPI Monitoring Dashboard
- Fraud Trend Analysis
- Risk Visualization

---

## Note

This project uses synthetic data for learning and portfolio purposes.

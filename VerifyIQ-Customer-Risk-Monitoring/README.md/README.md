# VerifyIQ - Customer Risk & Transaction Monitoring

## Project Overview
VerifyIQ is a data analytics project focused on customer risk assessment and transaction monitoring in a simulated banking/compliance environment.

The objective of this project is to identify high-risk customers, suspicious transaction patterns, and potential fraud indicators using SQL-driven analysis.

This project uses synthetic KYC and transaction datasets to replicate real-world financial compliance monitoring scenarios such as AML (Anti-Money Laundering), sanctions screening, and risk profiling.

---

## Business Problem
Financial institutions need to continuously monitor customer activity to detect suspicious behavior, regulatory risks, and compliance violations.

This project answers practical compliance-related questions such as:

- Which customers are classified as high risk?
- How many Politically Exposed Persons (PEPs) exist?
- Are sanctioned or FATF-risk customers present?
- Which transactions show suspicious movement patterns?
- Who are the highest-value transacting customers?

---

## Tools & Technologies Used
- PostgreSQL
- SQL
- Excel
- Power Query
- Data Cleaning
- Data Analysis
- Compliance Risk Analytics

---

## Project Workflow
In this project, I performed the complete end-to-end analytics workflow:

### Data Preparation
- Cleaned raw CSV datasets using Excel and Power Query
- Standardized customer and transaction records
- Prepared structured datasets for analysis

### Database Setup
- Imported datasets into PostgreSQL
- Created analysis-ready tables
- Performed joins between customer and transaction datasets

### Risk Analysis
Analyzed customer risk categories including:
- High-risk sectors
- Politically Exposed Persons (PEP)
- Sanctioned customers
- FATF risk exposure
- OFAC-related transaction risk

### Suspicious Transaction Monitoring
Investigated suspicious patterns such as:
- Structuring behavior
- Rapid fund movement
- High-value transaction anomalies
- Trade mispricing indicators

---

## Key Business Questions Answered
This project answers important business and compliance questions:

- Total customers in the system
- Distribution of customer types
- Count of high-risk customers
- PEP customer analysis
- Sanctioned customer identification
- FATF risk exposure analysis
- Total transaction volume
- Highest transaction amount by customer
- High-risk customer transaction behavior
- Suspicious activity pattern detection

---

## Project Structure
```text
VerifyIQ-Customer-Risk-Monitoring
│
├── data
├── sql
├── screenshots
└── README.md

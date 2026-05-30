# VerifyIQ — Customer Risk & Transaction Monitoring

> A real-world inspired banking compliance analytics project built using **SQL**, **PostgreSQL**, **Excel**, and **Power Query** to monitor customer risk profiles, suspicious transaction behaviour, and compliance exposure.

This project simulates how financial institutions identify high-risk customers, detect suspicious transactions, and enforce AML/compliance policies using data analytics — workflows commonly used by Risk, Fraud, and Compliance teams.

---

##  Table of Contents

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Key Analysis Performed](#key-analysis-performed)
- [Key Business Insights](#key-business-insights)
- [Screenshots](#screenshots)
- [Skills Demonstrated](#skills-demonstrated)
- [Relevant Roles](#relevant-roles)
- [Author](#author)

---

##  Project Overview

**VerifyIQ** is a customer risk monitoring and transaction analytics project designed to simulate real-world compliance analysis workflows.

The project focuses on identifying:

-  High-risk customers
-  Politically Exposed Persons (PEPs)
-  Sanctioned customers
-  FATF / OFAC risk flagged customers
-  Suspicious transaction behaviour
-  High transaction volume anomalies

---

##  Business Problem

Banks and financial institutions must continuously monitor customer activity to detect suspicious behaviour, fraud risks, and compliance violations.

This project answers critical business questions such as:

| Business Question | Analysis Performed |
|---|---|
| Which customers are classified as high risk? | Risk segmentation query |
| How many PEP customers exist? | PEP identification analysis |
| Are sanctioned entities present in the database? | Sanctions screening query |
| Which customers moved unusually high transaction volumes? | Top customer transaction analysis |
| What suspicious transaction patterns exist? | Suspicious activity detection |

---

##  Tech Stack

| Tool | Purpose |
|---|---|
| **PostgreSQL** | Database & query execution |
| **SQL** | Data extraction & risk analysis |
| **Excel** | Data cleaning & preprocessing |
| **Power Query** | ETL & data transformation |
| **CSV** | Raw data handling |

---

##  Project Structure

```text
VerifyIQ-Customer-Risk-Monitoring
│
├── data
│   ├── clients_clean.csv                   # Cleaned customer master data
│   └── transactions_with_fatf_ofac.csv     # Transaction data with FATF/OFAC flags
│
├── sql
│   └── queries.sql                         # All SQL analysis queries
│
├── screenshots
│   ├── total_clients.png
│   ├── total_transactions.png
│   └── top_customers_analysis.png
│
└── README.md
```

---

##  Key Analysis Performed

###  Customer Risk Analysis
- High-risk customer identification & segmentation
- Politically Exposed Persons (PEP) analysis
- Sanctions screening (OFAC flagged customers)
- FATF risk country exposure analysis
- Customer risk profile classification

###  Transaction Monitoring
- Total transaction volume analysis
- Top customer transaction behaviour
- Suspicious activity pattern detection
- High-value transaction monitoring
- Anomaly identification in transaction data

---

##  Key Business Insights

- A significant portion of customers were flagged under **FATF high-risk jurisdictions**, indicating elevated compliance exposure.
- **PEP customers** were identified and segmented for enhanced due diligence monitoring.
- **Sanctioned entities** detected in the customer database highlight the importance of continuous screening.
- Top customers by transaction volume showed **unusual activity patterns** warranting further investigation.
- Suspicious transaction clustering revealed potential **layering behaviour** commonly associated with money laundering.

---

##  Screenshots

###  Total Customers Analysis

![Total Customers](./VerifyIQ-Customer-Risk-Monitoring/screenshots/total_clients.png)

---

###  Total Transactions Analysis

![Total Transactions](./VerifyIQ-Customer-Risk-Monitoring/screenshots/total_transactions.png)

---

###  Top Customer Transaction Analysis

![Top Customers](./VerifyIQ-Customer-Risk-Monitoring/screenshots/top_customers_analysis.png)

---

##  Skills Demonstrated

- SQL Query Writing & Optimisation
- PostgreSQL Database Management
- AML & Compliance Data Analysis
- Risk Segmentation & Profiling
- Fraud & Suspicious Activity Detection
- Excel Data Cleaning
- Power Query (ETL)
- Business Analysis & Reporting
- Git & GitHub Version Control

---

##  Author

**Rachit Bajpai**

🔗 GitHub Project: [VerifyIQ-Customer-Risk-Monitoring](https://github.com/Rachit150501/VerifyIQ-Customer-Risk-Monitoring)

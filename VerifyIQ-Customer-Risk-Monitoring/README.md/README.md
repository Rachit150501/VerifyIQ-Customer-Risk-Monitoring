VerifyIQ - Customer Risk & Transaction Monitoring

About This Project :

I built this project to understand how customer risk analysis and transaction monitoring work in a banking/compliance environment.

The goal of this project is to identify risky customers, suspicious transaction patterns, and potential fraud indicators using SQL-based analysis.

This project uses synthetic KYC and transaction data to simulate real-world compliance monitoring scenarios.

-----------------------------------------------------------

Tools Used :

- PostgreSQL
- SQL
- Excel
- Power Query

-------------------------------------------------------------

What I Did
In this project, I worked on the complete data analysis workflow:

- Cleaned raw CSV datasets using Excel and Power Query

- Imported client and transaction datasets into PostgreSQL


- Created SQL queries to answer business and compliance-related questions

- Analyzed customer risk categories such as:
  - High-risk sectors
  - Politically Exposed Persons (PEP)
  - Sanctioned customers
  - FATF / OFAC risk exposure

- Investigated suspicious transaction patterns including:
  - Structuring behavior
  - Rapid fund movement
  - Trade mispricing indicators

- Performed JOIN-based analysis between customer and transaction data

--------------------------------------------------------------

Key Business Questions Answered
Some of the analysis questions explored in this project:

- How many total customers are in the system?
- What is the distribution of customer types?
- How many high-risk customers exist?
- How many PEP or sanctioned customers are present?
- What is the total transaction volume?
- Which customers moved the highest transaction amounts?
- Are high-risk customers involved in suspicious transactions?
- What suspicious patterns are visible in transaction activity?

--------------------------------------------------------------

Project Folder Structure :

VerifyIQ-Customer-Risk-Monitoring
│
├── data
├── sql
├── screenshots
└── README.md
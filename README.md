## Project Overview
This project is a Power BI dashboard designed to analyze bank transaction data and identify fraud patterns. The report provides a clear view of transaction volume, transaction value, success and failure rates, and fraud-related activity across multiple dimensions.

I built this dashboard by following a guided tutorial and customizing it to better understand transaction behavior and fraud indicators using real-world style banking data.

---

## Project Goal
The goal of this project is to:
- Understand overall transaction activity
- Monitor transaction trends over time
- Identify failed and fraudulent transactions
- Analyze fraud patterns by transaction type, region, and network attributes
- Enable drill-down analysis for individual transactions

---

## Business Use Case
This dashboard can support:
- Operations teams monitoring transaction health
- Risk and fraud teams identifying suspicious activity
- Business users analyzing transaction trends and regional performance

---

## Dashboard Pages

### 1️⃣ Home Page – Transaction Overview
Answers key questions such as:
- How many transactions occurred?
- What is the total transaction amount?
- How do transactions trend over time?
- What is the success vs failure rate?
- How many transactions are flagged as fraud?
- Which transaction types and regions contribute most to volume?

**Key KPIs:**
- Total Transactions
- Total Transaction Amount
- Success Rate / Failure Rate
- Fraudulent Transactions Count

---

### 2️⃣ Fraud Detection Page
Focused on identifying and analyzing fraud patterns.

Answers questions like:
- How many transactions are flagged as fraud?
- What is the total value of fraudulent transactions?
- What is the success vs failure rate of fraudulent transactions?
- Which transaction types, regions, bandwidth groups, and network slices show higher fraud activity?

**Key KPIs:**
- Total Fraudulent Transactions
- Total Fraudulent Amount
- Fraud Success vs Failure Count

---

### 3️⃣ Transaction Details Page
Provides transaction-level detail to support investigation and drill-down analysis.

Features:
- Individual transaction records
- Drill-through navigation from summary pages
- Detailed view for deeper analysis

---

## Dataset Description
- **Source:** Sample banking transaction dataset from tutorial  

---

## Tools & Technologies
- **Power BI Desktop**
- **Power Query** (data cleaning and transformation)
- **DAX** (KPI calculations and measures)
- **PowerPoint** (custom dashboard backgrounds)

---

## Features & Functionality
- Interactive KPI cards
- Line, bar, doughnut, and map visuals
- Slicers for dynamic filtering
- Drill-through navigation for detailed analysis
- Conditional formatting for better insights
- Custom page navigation

---

## Key Learnings
- Designing dashboards around business questions
- Translating transaction data into meaningful KPIs
- Using Power Query for clean and reliable data
- Applying DAX for analytical insights
- Building user-friendly and interactive Power BI reports

---

### Home Page – Transaction Overview
![Home Page](screenshots/home_page.png)

### Fraud Detection Page
![Fraud Detection](screenshots/fraud_detection_page.png)

### Transaction Details Page
![Transaction Details](screenshots/transaction_details_page.png)

---

## Notes
This project was built as a learning and portfolio project to strengthen Power BI skills in a banking and fraud-analysis context.

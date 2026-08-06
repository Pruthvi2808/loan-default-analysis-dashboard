# 📊 Loan Default Analysis Dashboard

## 📌 Project Overview

The Loan Default Analysis Dashboard is an interactive Business Intelligence solution built using Power BI, SQL, Power Query, DAX, and Microsoft Excel. The project analyzes 255,347 loan records across 19 attributes to evaluate loan performance, borrower demographics, credit risk, and default trends through interactive dashboards and KPI-driven reporting.

---

# 🎯 Problem Statement

Financial institutions generate large volumes of loan data that require continuous analysis to understand borrower behavior, monitor loan performance, and identify potential default trends. Manual analysis is time-consuming and often fails to provide timely insights.

This dashboard addresses that by providing an interactive platform to analyze:

* Loan Distribution
* Borrower Demographics
* Default Rate
* Credit Score Analysis
* Employment Type Analysis
* Income Analysis
* Financial Risk Metrics
* Year-over-Year Loan Growth

---

# 📂 Dataset Information

| Attribute | Details              |
| --------- | -------------------- |
| Dataset   | Loan Default Dataset |
| Records   | 255,347          |
| Columns   | 19               |
| File Type | CSV                  |

---

# 🛠 Technologies Used

* Power BI Desktop
* SQL
* Power Query
* DAX
* Microsoft Excel

---

# 🔄 Project Workflow

### Step 1
Imported the Loan Default dataset (CSV) and loaded it for cleaning and analysis using SQL.

### Step 2
Performed data cleaning and validation using SQL by checking for:

* Missing values
* Duplicate records
* Incorrect data types
* Data inconsistencies

### Step 3
Imported the cleaned dataset into Power BI Desktop.

### Step 4
Used Power Query to perform data transformation, data type validation, and data modeling before creating the Power BI dashboard.

### Step 5
Enabled Column Quality, Column Distribution, and Column Profile in Power Query to assess data quality and identify missing values, duplicate records, and data inconsistencies.

### Step 6
Created calculated columns, DAX measures, and KPIs to support the analysis and interactive reporting.

### Step 7
Developed a three-page interactive Power BI dashboard featuring KPIs, slicers, drill-through navigation, and interactive visualizations for loan performance and borrower analysis.

### Step 8
Published the report to Power BI Service.

---

# 📈 Dashboard Pages

## Page 1 - Loan Default & Overview

Dashboard includes:

* Loan Amount by Purpose
* Average Income by Employment Type
* Default Rate by Employment Type
* Average Loan Amount by Age Group
* Default Rate by Year

![Dashboard Page 1](Dashboard_Screenshots/Page1.png)

---

## Page 2 - Applicant Demographics & Financial Profile

Dashboard includes:

* Median Loan Amount by Credit Score
* Average Loan Amount by Age Group & Marital Status
* Total Loan Amount by Credit Score
* Loan Distribution by Dependents
* Number of Loans by Education Level

![Dashboard Page 2](Dashboard_Screenshots/Page2.png)

---

## Page 3 - Financial Risk Metrics

Dashboard includes:

* YoY Loan Amount Growth
* YoY Default Loan Growth
* Credit Score vs Marital Status Analysis
* Income Bracket Analysis using Decomposition Tree

![Dashboard Page 3](Dashboard_Screenshots/Page3.png)

---

# 📊 KPIs Developed

* Total Loan Amount
* Average Loan Amount
* Default Rate (%)
* Average Income
* Median Loan Amount
* Year-over-Year Loan Growth
* Year-over-Year Default Loan Growth

---

# 📉 Key Insights

* **Employment status is a strong default predictor** — unemployed borrowers defaulted at 13.55%, nearly 4 points higher than full-time employed borrowers (9.46%).
* **Default rate falls as education level rises** — from 12.88% (High School) down to 10.59% (PhD), a consistent step-down across every education tier.
* **A co-signer meaningfully reduces risk** — default rate drops from 12.87% (no co-signer) to 10.36% (with a co-signer).
* **Borrowers with both a mortgage and dependents default least** (9.79%), likely reflecting greater financial stability and stake in repayment.
* **Loan purpose does not meaningfully affect volume** — total loan amount was evenly distributed (~$6.5B each) across Home, Business, Education, Auto, and Other, making it a weak standalone risk signal.

---

# ✨ Features

* Interactive Slicers
* Drill-through Navigation
* Cross-filtering between visuals
* Dynamic DAX Measures
* Multiple Chart Types
* Decomposition Tree Analysis

---

# 📚 Skills Demonstrated

* Data Cleaning & Validation
* SQL Querying
* Power Query (Data Transformation & Data Modeling)
* DAX
* KPI Development
* Dashboard Development
* Data Visualization
* Credit Risk Analysis

---

# 📌 Conclusion

This project is a self-directed portfolio exercise analyzing 255,347 loan records to practice end-to-end BI workflow — from data cleaning and modeling in SQL/Power Query to building an interactive, risk-focused Power BI dashboard. It demonstrates the ability to identify default risk drivers (employment, education, co-signer status) and communicate them clearly using SQL, Power Query, and DAX.

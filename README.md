# 🏦 Bank Loan Analytics Dashboard

An end-to-end Business Analyst project that transforms raw banking loan data into interactive dashboards, enabling stakeholders to monitor lending performance, assess credit risk, and make data-driven decisions.

---

## 📌 Project Overview

Banks issue thousands of loans daily across multiple branches, states, and customer segments — but without a consolidated view, leadership struggles to answer simple questions: *Which loan products are performing well? Where is default risk concentrated? Which branches need attention?*

This project builds a complete reporting pipeline — from raw transactional data to an interactive BI dashboard — giving stakeholders a single source of truth for loan portfolio health, using a real-world banking dataset of **65,000+ loan records across 15 banks and 17 states**, with **53 data fields** covering borrower demographics, loan terms, repayment, and risk indicators.

---

## ❗ Problem Statement

The bank's loan data was scattered across raw transactional records (Excel exports) with no centralized reporting, making it difficult for management to:
- Track total loan disbursement and collection performance
- Identify high-risk loan categories and default/delinquency trends
- Understand loan distribution across states, demographics, and product types
- Spot underperforming branches or rising NPAs (Non-Performing Assets) early
- Maintain a standardized definition of data fields across teams

Decisions were being made reactively, without a clear, real-time view of portfolio health.

---

## ✅ Solution

Designed and built a **Bank Loan Analytics Dashboard** using a structured BA workflow:

1. **Requirement Gathering** – Defined KPIs and stakeholder reporting needs (loan volume, funded amount, default rate, demographic distribution, etc.)
2. **Data Profiling & Mapping** – Audited 53 raw fields (Account ID, Loan Status, Grade/Sub-Grade, Disbursement Date, Recoveries, etc.) and created a standardized data dictionary (`Column_Mapping_Document.xlsx`)
3. **Data Cleaning** – Resolved inconsistent date formats, duplicate state codes, and null values across 65,000+ records
4. **Database Integration** – Loaded cleaned data into a SQL database under a structured banking schema
5. **BI Tool Connection** – Connected SQL database to Power BI / Tableau and built a relational data model with necessary joins
6. **Dashboard Development** – Built an interactive, multi-view dashboard covering loan performance, risk, and demographics
7. **Quality Assurance** – Validated dashboard figures against raw database records to ensure accuracy
8. **Stakeholder Reporting** – Delivered final insights via dashboard + presentation deck

**Tools Used:** Excel · SQL · Power BI · Tableau

---

## 🗂️ Dataset Overview

| Attribute | Detail |
|---|---|
| Total Records | 65,000+ loan accounts |
| Fields/Columns | 53 (borrower info, loan terms, repayment, risk) |
| Banks Covered | 15 |
| States Covered | 17 |
| Key Fields | Loan Amount, Funded Amount, Interest Rate, Loan Status, Grade/Sub-Grade, Disbursement Date, Delinquency Flags, Recoveries, Caste/Religion (demographics), Verification Status |

Full field-level data dictionary available in [`Column_Mapping_Document.xlsx`](./Column_Mapping_Document.xlsx).

---

## 📊 Key Metrics (KPIs) Tracked

| KPI | Purpose |
|---|---|
| Total Loan Applications | Measures lending activity volume |
| Total Funded Amount | Total value of loans disbursed |
| Total Amount Received | Tracks repayment/collection performance |
| Loan Status Distribution | Active, Fully Paid, Cancelled, Transferred, NPA breakdown |
| Default Rate by State | Geographic risk concentration |
| Product-Wise Loan Volume | Performance by loan purpose (Home, Business, Education, etc.) |
| Grade/Sub-Grade Distribution | Portfolio risk classification by credit grade |
| Demographic Loan Distribution | Caste/category-wise loan disbursement for compliance tracking |
| Loan Purpose vs Funded Amount | Identifies which loan types receive highest funding and risk |
| Delinquency Rate | Tracks borrowers with missed/overdue payments |

---

## 🖥️ Dashboard Features
- **Product-Wise Loan Breakdown** – Loan amount segmented by purpose category (Home, Business, Trade, Agriculture, etc.)
- **Loan Status Distribution** – Visual breakdown of Active, Fully Paid, Cancelled, and Transferred loans
- **State-Wise Default Rate Map** – Geographic heat map of loan defaults across India
- **Demographic Loan Distribution** – Caste/category-wise loan disbursement view
- **Loan Purpose vs Funded Amount** – Comparison of funding across loan categories and statuses
- Interactive filters: Purpose Category, Loan Status, Caste/Category

---

## 🎯 Outcome / Impact
- Consolidated 65,000+ scattered loan records (53 fields) into one interactive, single-source-of-truth dashboard
- Reduced manual reporting effort through a standardized data model and field dictionary
- Enabled faster identification of high-default-risk states and loan categories
- Gave stakeholders a real-time view of **₹719M+** in funded loans across **64,278 applications**
- Improved transparency in demographic loan distribution for compliance reporting
- Created a reusable data-mapping standard for future banking analytics projects

---

## 🛠️ Tech Stack
- **Data Analysis:** Excel (Advanced), SQL
- **Visualization:** Power BI, Tableau
- **Documentation:** Column Mapping Document, Project Presentation Deck

---

## 📂 Repository Structure
```
├── README.md
├── Loan Project Problem Statement File   # Problem statement & solution writeup
├── Column_Mapping_Document.xlsx          # Field definitions & data dictionary
├── Bank_Data_Analystics.xlsx             # Raw dataset (65,000+ records, 53 fields)
├── Loan_Analytics.pptx                   # Project presentation & KPI documentation
├── dashboard_screenshot.png              # Dashboard preview
```

---

## 👤 Author
**Amit Yadav**
Business Analyst | SQL, Power BI, Tableau, Excel
📧 amityadav1948951@gmail.com | 📍 Mumbai, Maharashtra, India

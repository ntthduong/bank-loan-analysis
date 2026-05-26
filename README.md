# Bank Loan Analysis Dashboard | Power BI

## 1. Project Overview

This project is an interactive **Power BI dashboard** built to analyze bank loan portfolio performance. The dashboard focuses on monitoring key lending metrics such as loan applications, funded amount, amount received, average interest rate, debt-to-income ratio, and good/bad loan segmentation.

The main objective of this project is to practice building a finance-domain analytics dashboard that helps business users understand loan portfolio performance, repayment behavior, and potential credit risk patterns.

> This is a guided portfolio project created for learning and practice purposes, with customization in KPI interpretation, dashboard structure, and business insight presentation.

---

## 2. Business Questions

The dashboard was designed to answer the following business questions:

- How many loan applications were received?
- What is the total funded amount?
- What is the total amount received from borrowers?
- What is the average interest rate?
- What is the average debt-to-income ratio?
- What percentage of loans are classified as good loans and bad loans?
- How does loan performance vary by state, loan term, employment length, loan purpose, and home ownership?
- Which loan segments may require closer monitoring?

---

## 3. Dataset Description

The dataset contains historical bank loan records, including loan amount, funded amount, repayment amount, loan status, borrower information, loan purpose, loan grade, interest rate, debt-to-income ratio, and loan issue date.

Main fields used in the analysis include:

| Field | Description |
|---|---|
| `id` | Unique loan/application ID |
| `loan_status` | Current status of the loan |
| `loan_amount` | Loan amount requested or approved |
| `total_payment` | Total amount received from borrower |
| `int_rate` | Interest rate of the loan |
| `dti` | Debt-to-income ratio |
| `issue_date` | Loan issue date |
| `address_state` | Borrower's state |
| `term` | Loan repayment term |
| `emp_length` | Borrower's employment length |
| `purpose` | Purpose of the loan |
| `home_ownership` | Borrower's home ownership status |
| `grade` | Loan grade |
| `sub_grade` | Loan sub-grade |

---

## 4. Tools Used

- **Power BI**: Dashboard development and data visualization
- **Power Query**: Data cleaning and transformation
- **DAX**: KPI measures and calculated metrics
- **Data Visualization**: KPI cards, charts, slicers, and interactive report pages
- **Business Analysis**: Loan portfolio monitoring and risk-related insight generation

---

## 5. Dashboard Structure

The Power BI report includes three main pages:

### 5.1 Summary Page

The Summary page provides an executive-level overview of the bank loan portfolio.

Main metrics include:

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio
- Good Loan Percentage
- Bad Loan Percentage
- Loan Status Breakdown
- Month-to-Date and Month-over-Month performance

This page helps users quickly evaluate overall lending performance and portfolio quality.

---

### 5.2 Overview Page

The Overview page provides a deeper breakdown of loan performance across different borrower and loan dimensions.

Main analysis areas include:

- Monthly loan trends
- Loan distribution by state
- Loan distribution by loan term
- Loan amount by employment length
- Loan amount by loan purpose
- Loan amount by home ownership

This page helps users explore portfolio patterns by geography, borrower profile, and loan characteristics.

---

### 5.3 Details Page

The Details page provides a loan-level view for detailed investigation.

It allows users to review individual loan records, including:

- Loan ID
- Purpose
- Home Ownership
- Grade
- Sub-grade
- Loan Status
- Funded Amount
- Amount Received
- Interest Rate
- Debt-to-Income Ratio

This page supports record-level monitoring and more detailed loan investigation.

---

## 6. Key KPIs

| KPI | Description |
|---|---|
| Total Loan Applications | Total number of loan applications |
| Total Funded Amount | Total loan amount funded by the bank |
| Total Amount Received | Total repayment amount received from borrowers |
| Average Interest Rate | Average interest rate across all loans |
| Average DTI | Average debt-to-income ratio |
| Good Loan Percentage | Percentage of loans with healthy repayment status |
| Bad Loan Percentage | Percentage of loans with problematic repayment status |
| MTD Metrics | Month-to-date performance indicators |
| MoM Metrics | Month-over-month performance comparison |

---

## 7. Good Loan vs Bad Loan Classification

Loans are categorized into two main groups:

### Good Loans

Good loans include loans with healthy repayment status, such as:

- Fully Paid
- Current

### Bad Loans

Bad loans include loans with problematic repayment status, such as:

- Charged Off

This classification helps evaluate loan portfolio quality and identify potential credit risk patterns.

---

## 8. Key Insights

Some key observations from the dashboard include:

- Good loan and bad loan segmentation provides a clear overview of portfolio quality.
- Funded amount, amount received, interest rate, and DTI are important indicators for monitoring loan performance.
- Loan performance varies across borrower characteristics such as employment length, home ownership, loan purpose, and grade.
- Geographic analysis helps identify regional loan distribution patterns.
- Monthly trend analysis supports monitoring of portfolio growth and repayment performance over time.

---

## 9. Skills Practiced

Through this project, I practiced:

- Building an end-to-end Power BI dashboard
- Creating KPI cards and interactive report pages
- Cleaning and transforming data using Power Query
- Creating DAX measures for business KPIs
- Using slicers and filters to improve dashboard interactivity
- Designing multi-page dashboards for summary and detailed analysis
- Translating raw loan data into business insights
- Presenting finance-related analysis in a structured way

---

## 10. Project Structure

```text
bank-loan-analysis/
│
├── BankLoan.pbix
├── README.md
└── data/
```

---

## 11. How to View the Dashboard

1. Download the `BankLoan.pbix` file from this repository.
2. Open the file using Power BI Desktop.
3. Explore the dashboard pages:
   - Summary
   - Overview
   - Details
4. Use slicers and filters to analyze different loan segments.

---

## 12. Notes

Dashboard screenshots are not included in this version of the repository. The full interactive dashboard can be viewed by downloading and opening the `.pbix` file in Power BI Desktop.

---

## 13. Acknowledgement

This project was built as a guided learning project based on a public Power BI tutorial. The purpose of this repository is to demonstrate hands-on practice in Power BI dashboard development, financial KPI analysis, and data storytelling for a Data Analyst portfolio.

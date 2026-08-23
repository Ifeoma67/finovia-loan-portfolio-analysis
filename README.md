# Finovia Loan Portfolio & Financial Performance Analysis

## Project Overview

Finovia Global Finance is a simulated digital consumer lender operating across multiple markets. This project uses Power BI to turn loan-level data into an interactive management report covering **Loan Operations, Loan Outcomes, and Financial Performance**.

The purpose of the dashboard is to help decision-makers monitor lending activity, compare branches and products, assess repayment and default behaviour, and understand how collections and lending costs translate into profitability.

> **Portfolio note:** This project was developed using a simulated financial-services dataset. The Power BI report design, visualisation, analysis, and business interpretation presented here form part of my personal analytics portfolio.

---

## Business Problem

Management needed a consolidated view of lending performance. Although the underlying data contained the necessary information, trends and performance differences were difficult to interpret without an interactive reporting layer.

The analysis focused on four management questions:

1. How efficiently is the organisation processing and distributing loans?
2. Which branches, products, and markets account for the greatest lending activity?
3. How strong are repayment and default outcomes across the portfolio?
4. How effectively does lending activity translate into collections and profitability?

---

## Project Objectives

- Monitor loan volumes and borrower activity
- Evaluate average approval time and credit-limit utilisation
- Compare lending activity across branches, products, and countries
- Assess repayment, default, and repeat-borrower performance
- Compare branch and product loan outcomes
- Monitor billed amounts, collections, and outstanding balances
- Evaluate lending costs, net income, collection rate, and profit margin
- Build an intuitive three-page Power BI management dashboard
- Translate dashboard findings into clear business insights and recommendations

---

## Dataset

The project uses a simulated lending dataset covering activity across **2023 and 2024**.

The data includes:

- Loan and borrower identifiers
- Loan officers and officer tiers
- Products, branches, and countries
- Repayment plans and loan status
- Approval wait time and credit utilisation
- Repeat-borrower status
- Processing, servicing, assessment, and funding costs
- Amount billed and amount collected
- Net income

A full field-level description is available in [`documentation/data_dictionary.md`](documentation/data_dictionary.md).

---

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Loans | 4,000 |
| Unique Borrowers | 2,000 |
| Average Approval Time | 5.5 days |
| Average Credit Utilisation | 60.4% |
| Loans per Officer | 40 |
| Repaid Loans | 2,717 |
| Repayment Rate | 67.93% |
| Defaulted Loans | 241 |
| Default Rate | 6.03% |
| Repeat Borrower Rate | 50% |
| Amount Billed | £795M |
| Amount Collected | £683M |
| Outstanding Balance | £112M |
| Total Cost of Lending | £559M |
| Net Income | £124M |
| Collection Rate | 85.9% |
| Profit Margin | 18.2% |

---

# Dashboard

## 1. Loan Operations

![Loan Operations Dashboard](images/loan_operations_dashboard.png)

The Loan Operations page provides a high-level view of portfolio scale and operational efficiency.

### What it monitors
- Total loans
- Unique borrowers
- Average approval time
- Credit utilisation
- Loans per officer
- Monthly loan volume
- Loans by country
- Loans by product
- Loans by branch

### Key observations
- Finovia issued **4,000 loans** to **2,000 unique borrowers**.
- Average approval time was approximately **5.5 days**.
- Average credit utilisation was approximately **60.4%**.
- Each loan officer handled an average of **40 loans**.
- **Auto Credit** recorded the highest product volume at **528 loans**.
- **Riverside** handled the largest branch loan volume at **708 loans**.

---

## 2. Loan Outcomes

![Loan Outcomes Dashboard](images/loan_outcomes_dashboard.png)

The Loan Outcomes page evaluates portfolio quality through repayment, default, and repeat-borrower performance.

### What it monitors
- Repayment rate and repaid loans
- Default rate and defaulted loans
- Repeat-borrower rate
- Monthly repayment and default performance
- Repayment performance by branch
- Repayment and default performance by product

### Key observations
- **2,717 loans were repaid**, producing a **67.93% repayment rate**.
- **241 loans defaulted**, producing a **6.03% default rate**.
- Repeat borrowers accounted for approximately **50%**.
- The dashboard compares branch repayment performance with a **75% target**, showing that overall performance remains below the desired level.

---

## 3. Financial Performance

![Finance Dashboard](images/finance_dashboard.png)

The Finance page connects lending activity with collections, costs, and profitability.

### What it monitors
- Net income
- Total cost of lending
- Profit margin
- Amount billed
- Collection rate
- Outstanding balance
- Net income by country
- Monthly net income
- Cost-of-lending breakdown
- Net income by branch

### Financial headline
- **£795M** billed
- Approximately **$683M** collected
- Approximately **$112M** outstanding
- Approximately **$559M** total cost of lending
- Approximately **$124M** net income
- **85.9%** collection rate
- **18.2%** profit margin

---

## Key Business Insights

### 1. Loan volume should not be used as the only measure of branch performance
The dashboard shows clear differences between loan volume, repayment outcomes, and profitability. Management should therefore assess branches using a balanced set of operational, risk, and financial KPIs.

### 2. Repayment performance is below the dashboard target
The overall repayment rate of **67.93%** is below the **75% target**, indicating a need to investigate the branches, products, or borrower segments contributing most to the gap.

### 3. Default risk should be monitored below portfolio level
The overall default rate is **6.03%**, but portfolio-level averages can hide differences between products and branches. Product- and branch-level monitoring is therefore important for early risk identification.

### 4. Outstanding collections remain financially material
Approximately **£112M** remains outstanding within the dataset. Improving collections could therefore have a meaningful impact on financial performance.

### 5. Profitability should be considered alongside portfolio growth
Finovia generated approximately **£124M net income** with an **18.2% profit margin**. This reinforces the need to compare lending growth with collections, cost, and profitability rather than viewing volume in isolation.

---

## Business Recommendations

- Investigate branches and products with below-average repayment performance.
- Evaluate high-volume branches using repayment, default, collection, and profitability measures alongside loan count.
- Analyse the outstanding balance by branch, product, and loan status to prioritise collection activity.
- Monitor product-level default trends to identify emerging credit-risk concentrations.
- Benchmark stronger-performing branches and identify practices that could be replicated.
- Use a balanced performance scorecard combining operational, risk, and financial KPIs.

---

## Report Development

The original training brief supplied a prepared lending data model and measures as the analytical starting point. This portfolio project focuses on developing the **interactive Power BI reporting layer**, visual design, KPI presentation, cross-page navigation, analysis, and management interpretation.

### Power BI features demonstrated
- Multi-page report design
- KPI cards
- Page navigation
- Slicers and filters
- Time-series analysis
- Geographic analysis
- Matrix visualisation
- Conditional formatting
- Product and branch comparisons
- Decomposition analysis
- Management dashboard design
- Data storytelling

---

## Tools

- **Microsoft Power BI** — dashboard development and visual analysis
- **Microsoft Excel** — source data format

---

## Skills Demonstrated

- Business requirement interpretation
- Dashboard design
- KPI analysis
- Loan portfolio analysis
- Repayment and default analysis
- Financial performance analysis
- Product performance analysis
- Branch performance analysis
- Trend analysis
- Data visualisation
- Data storytelling
- Insight generation
- Business recommendation development

---

## Repository Structure

```text
finovia-loan-portfolio-analysis/
│
├── README.md
│
├── data/
│   └── Finovia_Loan_Data.xlsx
│
├── images/
│   ├── loan_operations_dashboard.png
│   ├── loan_outcomes_dashboard.png
│   └── finance_dashboard.png
│
└── documentation/
    ├── data_dictionary.md
```

---

## How to Explore the Project

The dashboard screenshots can be viewed directly in this README.

---

## Data Disclaimer

Finovia Global Finance is a simulated company and the dataset used in this project is training data. The analysis is intended to demonstrate data analytics, Power BI, business intelligence, and data storytelling skills.

---

## Author

**Ifeoma Edeh**

Data Analyst | Power BI | Excel | SQL | Data Visualisation

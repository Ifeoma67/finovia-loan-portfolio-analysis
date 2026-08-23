# Finovia Data Dictionary

The Finovia dataset contains loan, borrower, officer, product, branch, operational, risk, cost, and financial fields.

| Field | Description | Data Type |
|---|---|---|
| LoanID | Unique identifier for each loan account | Text |
| DisbursementDate | Date the loan was issued | Date |
| BorrowerID | Unique identifier for each borrower | Text |
| BorrowerName | Full name of the borrower | Text |
| Gender | Gender of the borrower | Text |
| Age | Borrower's age at the time of the loan | Whole Number |
| OfficerID | Unique identifier for each loan officer | Text |
| OfficerName | Full name of the loan officer | Text |
| OfficerTier | Officer seniority: Junior, Senior, or Lead | Text |
| ProductID | Unique identifier for the loan product | Text |
| ProductName | Name of the loan product | Text |
| BranchID | Unique identifier for the branch | Text |
| BranchName | Name of the branch | Text |
| Country | Country where the branch operates | Text |
| RepaymentPlan | Repayment plan applied: 6, 12, 24, or 36 months | Text |
| LoanPurpose | Reason for the loan | Text |
| LoanStatus | Current status: Repaid, Active, Late, or Defaulted | Text |
| LoanTenureDays | Number of days the loan has been on the books | Whole Number |
| ApprovalWaitDays | Days from application to disbursement | Whole Number |
| LimitUtilisationPercent | Percentage of the approved credit limit drawn | Percentage |
| RepeatBorrowerFlag | Whether the borrower has borrowed before: Y or N | Text |
| ProcessingCost | Cost to originate and process the loan | Currency |
| ServicingCost | Ongoing cost of servicing the loan | Currency |
| CreditAssessmentCost | Cost of credit checks and risk assessment | Currency |
| FundingCost | Capital advanced to fund the drawdown | Currency |
| TotalCost | Sum of all cost components | Currency |
| AmountBilled | Principal plus interest and fees billed | Currency |
| AmountCollected | Amount repaid and collected to date | Currency |
| NetIncome | Amount collected minus total cost | Currency |
| Profit Margin | Net Income ÷ Amount Collected

## Dataset Scope

- **Period:** 2023–2024
- **Domain:** Consumer and small-business lending
- **Company:** Simulated
- **Use:** Educational and portfolio purposes

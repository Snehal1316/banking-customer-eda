
# Banking Customer Behaviour Analysis
## Business Insights Report

### 1. Project Overview
- Dataset: Synthetic banking customer data
- Total customers: 1,200
- Total columns: 19
- Project type: Exploratory Data Analysis (EDA)
- Tools: Python, Pandas, NumPy, Matplotlib, Seaborn

### 2. Data Quality
- Duplicate rows: 0
- Duplicate customer IDs: 0
- Missing values initially: 105
- Missing values after treatment: 0
- Median imputation was used for selected numerical columns.

### 3. Customer Demographics
- Average customer age: 45.69 years
- Largest age group: 61–70 years (245 customers)
- Highest average income: Age group 51–60
- Highest average satisfaction: Age group 41–50

### 4. Account Distribution
- Savings: 669 customers (55.75%)
- Salary: 315 customers (26.25%)
- Current: 216 customers (18.00%)
- Metro customers: 348

### 5. Transaction Behaviour
- Current account customers had the highest average monthly transactions.
- Current account customers also had the highest average transaction value.
- Savings accounts represented the largest customer segment.

### 6. Digital Banking
- Digital banking users: 942 (78.5%)
- Non-digital users: 258 (21.5%)
- Average monthly transactions:
  - Digital users: 30.60
  - Non-digital users: 15.71

### 7. Loan Behaviour
- Customers with active loans: 432 (36%)
- Average loan amount among active-loan group: INR 738,302.09
- Total missed payments in active-loan group: 238
- Average missed payments in active-loan group: 0.55

### 8. Customer Churn
- Churned customers: 46
- Churn rate: 3.83%
- Churned customers had:
  - Lower average monthly transactions
  - More average complaints
  - Lower average satisfaction
  - More average missed payments

### 9. Correlation Findings
- Monthly transactions and digital transaction percentage: 0.59
- Monthly income and account balance: 0.56
- Loan amount and missed payments: 0.41
- Complaints and satisfaction: -0.32

### 10. Business Recommendations
1. Improve support for customers who report complaints.
2. Encourage digital banking adoption among non-digital customers.
3. Monitor customers with repeated missed loan payments.
4. Investigate factors associated with lower customer satisfaction.
5. Develop customer retention strategies for potentially at-risk customers.

### 11. Conclusion
The analysis highlights customer demographics, account preferences,
transaction activity, digital adoption, loan behaviour and churn patterns.

The findings can help a bank identify areas for improving customer
experience, digital engagement and retention.

Note: This is a synthetic practice dataset. Findings do not represent
the performance of an actual bank. Correlation does not imply causation.

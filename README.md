
# Banking Customer Behaviour Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on 1,200 synthetic banking customer records using Python. The objective is to understand customer demographics, account activity, digital banking adoption, loan behaviour, and customer churn while identifying meaningful business insights.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Objectives

- Analyse customer demographics and age distribution.
- Understand account types and transaction behaviour.
- Explore digital banking adoption.
- Analyse loan behaviour and missed payments.
- Investigate customer churn and satisfaction.
- Identify relationships between numerical variables.

## Data Cleaning and Preparation

| Metric | Result |
|---|---:|
| Original records | 1,200 |
| Original columns | 19 |
| Duplicate rows | 0 |
| Duplicate customer IDs | 0 |
| Initial missing values | 105 |
| Missing values after treatment | 0 |

**Data cleaning techniques:**
- Checked and handled missing values.
- Used median imputation for selected numerical columns.
- Verified duplicate records and customer IDs.
- Prepared the cleaned dataset for analysis.

## Key Findings

### 1. Customer Demographics

- Average customer age: **45.69 years**.
- Largest age group: **61–70 years**, with 245 customers.

### 2. Account Distribution

| Account Type | Customers | Percentage |
|---|---:|---:|
| Savings | 669 | 55.75% |
| Salary | 315 | 26.25% |
| Current | 216 | 18.00% |

Savings accounts represent the largest share of the customer base.

### 3. Digital Banking Adoption

- Digital banking users: **942 (78.5%)**.
- Non-digital banking users: **258 (21.5%)**.
- Average monthly transactions:
  - Digital users: **30.60**
  - Non-digital users: **15.71**

Digital banking users make approximately twice as many monthly transactions as non-digital users.

### 4. Loan Behaviour

- Active loan customers: **432 (36%)**.
- Average loan amount among active loan customers: **₹738,302.09**.
- Total missed payments: **238**.

These findings highlight the importance of monitoring loan repayment behaviour.

### 5. Customer Churn Analysis

- Churned customers: **46**.
- Customer churn rate: **3.83%**.
- Churned customers showed more complaints and slightly lower satisfaction.

Customer complaints and satisfaction may be useful indicators when investigating customer retention.

### 6. Correlation Analysis

| Variables | Correlation |
|---|---:|
| Monthly transactions and digital transaction percentage | 0.59 |
| Monthly income and account balance | 0.56 |
| Loan amount and missed payments | 0.41 |
| Complaints and satisfaction | -0.32 |

The results indicate moderate positive and negative relationships between selected variables. Correlation does not establish causation.

## Data Visualizations

The project includes five visualizations:

1. Customer Age Distribution
2. Customer Distribution by Account Type
3. Digital Banking Adoption
4. Customer Satisfaction by Churn Status
5. Correlation Heatmap

All charts are saved in the `outputs/charts/` directory.

## Business Recommendations

Based on the analysis:

1. **Improve Customer Support:** Address complaints promptly to improve customer satisfaction.
2. **Promote Digital Banking:** Encourage non-digital users to adopt digital banking services.
3. **Monitor Loan Repayments:** Identify customers with missed payments and improve repayment monitoring.
4. **Investigate Customer Dissatisfaction:** Analyse complaints and satisfaction levels to identify potential churn factors.
5. **Strengthen Customer Retention:** Develop targeted retention strategies for customers showing signs of dissatisfaction.

## Project Limitations

- The dataset is synthetic and does not represent actual banking customers.
- Correlation does not imply causation.
- The findings should not be interpreted as actual bank performance.
- Further analysis using real-world data would be required for practical business decisions.

## Conclusion

This project demonstrates practical skills in Python-based data cleaning, exploratory data analysis, statistical analysis, data visualization, and business insight generation.

It provides an understanding of banking customer behaviour and demonstrates how data analysis can support business decision-making.

## Repository Structure

```text
Banking-Customer-EDA/
│
├── data/
│   └── banking_customer_behaviour_synthetic.csv
│
├── notebooks/
│   └── banking_customer_eda.ipynb
│
├── outputs/
│   ├── charts/
│   ├── reports/
│   └── banking_customer_behaviour_cleaned.csv
│
├── README.md
└── requirements.txt
```

## How to Run This Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `notebooks/banking_customer_eda.ipynb`.
5. Run the notebook cells to explore the analysis.

## Privacy and Data Disclaimer

This project uses entirely synthetic banking customer data created for educational and portfolio purposes. It contains no real customer information and does not represent the performance of any actual financial institution.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Banking and Finance  
**Level:** Beginner  
**Author:** Snehal

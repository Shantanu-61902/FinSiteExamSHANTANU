# 📊 FinSight Bank Loan Risk Analysis & Exploratory Data Analysis

## Project Overview

This project focuses on performing a comprehensive Exploratory Data Analysis (EDA) on a large-scale banking dataset provided by FinSight Bank. The objective is to understand customer behavior, identify risk factors associated with loan defaults, clean and prepare the data, and derive meaningful business insights that can support credit risk management and lending decisions.

---

## Dataset Description

The analysis combines multiple banking datasets linked through a common `loan_id` key, including:

* Loan Master Data
* Loan Performance Records
* Customer Bureau Information
* Credit Card Behavior
* Payment History
* Monthly EMI Tracking
* Loan Enquiry Bureau Data
* Collateral Asset Details
* Branch & Regional Economic Indicators

---

## Project Objectives

### Data Acquisition & Cleaning

* Loaded and integrated multiple CSV datasets.
* Performed memory optimization using datatype downcasting.
* Identified and handled orphan records during joins.
* Detected and corrected data quality issues.
* Managed missing values using appropriate imputation techniques.
* Applied winsorization to reduce the impact of extreme outliers.

### Exploratory Data Analysis

* Analyzed loan default distribution.
* Examined customer creditworthiness through CIBIL score analysis.
* Studied income, debt-to-income ratio, interest rates, and repayment behavior.
* Investigated feature distributions and skewness.
* Performed correlation analysis between financial variables.
* Generated visualizations to identify patterns associated with loan defaults.

### Statistical Analysis

* Conducted hypothesis testing on important financial variables.
* Calculated effect sizes to measure practical significance.
* Evaluated relationships between borrower characteristics and loan performance.

---

## Key Insights

* Lower CIBIL scores are strongly associated with higher default rates.
* Customers with higher debt-to-income ratios exhibit increased credit risk.
* Several financial variables showed significant skewness, requiring transformation and outlier treatment.
* Credit utilization and repayment history emerged as important indicators of loan performance.
* Economic and regional factors contribute to variations in default behavior.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Statsmodels
* Scikit-Learn

---

## Skills Demonstrated

* Data Cleaning & Preprocessing
* Data Integration & Feature Engineering
* Exploratory Data Analysis (EDA)
* Statistical Testing
* Data Visualization
* Credit Risk Analysis
* Business Insight Generation

---

## Repository Structure

```text
├── data/
│   ├── loans_master.csv
│   ├── loan_performance.csv
│   ├── customer_bureau.csv
│   └── ...
├── notebooks/
│   └── EDA_Exam.ipynb
├── outputs/
│   ├── plots/
│   └── reports/
├── README.md
```

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow, starting from raw data acquisition and cleaning to advanced exploratory analysis and business insight generation. The findings can help financial institutions improve risk assessment, optimize lending strategies, and reduce loan default rates through data-driven decision-making.

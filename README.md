# Lending Club Loan Data Analysis

## Project Overview
This project analyzes loan data from Lending Club to understand borrower behavior, loan trends, and factors that contribute to loan default.

The main goal of this analysis is to identify patterns in defaulters and derive meaningful business insights using Exploratory Data Analysis (EDA).

---

## Problem Statement
Financial institutions face major risks when approving loans.  
This project helps in understanding:

- Which borrowers are more likely to default
- How loan amount varies over years
- Impact of income, employment length, home ownership, and purpose on loan repayment
- Trends in loan approvals and defaults

---

## Dataset Information
The dataset contains information about loan applicants such as:

- Loan Amount
- Interest Rate
- Annual Income
- Loan Status
- Employment Length
- Home Ownership
- Purpose of Loan
- Address State
- Issue Date

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Data Cleaning Steps

The following preprocessing steps were performed:

- Removed unnecessary columns
- Handled missing values
- Converted date columns
- Created new derived columns
- Filtered invalid records

---

## Exploratory Data Analysis (EDA)

The analysis includes:

### Univariate Analysis
- Loan Status Distribution
- Annual Income Distribution
- Loan Amount Distribution
- Interest Rate Analysis
- Employment Length Analysis

### Bivariate Analysis
- Loan Status vs Annual Income
- Loan Status vs Purpose
- Loan Amount vs Year
- Interest Rate vs Default Rate
- State-wise Defaulter Analysis

---

## Key Insights

- Higher loan amounts increased significantly over the years.
- Certain loan purposes showed higher default rates.
- Borrowers with lower annual income were more likely to default.
- Some states had noticeably higher percentages of defaulters.
- Interest rate and loan amount showed strong relation with defaults.

---

## Project Structure

```bash
LendingClub-Loan-Analysis/
│
├── data/
│   └── loan.csv
│
├── notebooks/
│   └── Lending_Club_Analysis.ipynb
│
├── images/
│   └── charts_and_graphs
│
├── README.md
│
└── requirements.txt

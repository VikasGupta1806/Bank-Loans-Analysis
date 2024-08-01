
# Bank Loans Analysis Project

This project analyzes bank loan data to gain insights into customer profiles, loan characteristics, and repayment behaviors using SQL and Tableau.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data](#data)
3. [Analysis](#analysis)
4. [SQL Queries](#sql-queries)
5. [Tableau Dashboard](#tableau-dashboard)
6. [Setup](#setup)
7. [Usage](#usage)
8. [Results](#results)
9. [Contributing](#contributing)
10.[License](#license)

## Project Overview

This project involves analyzing a dataset of bank loans to uncover patterns and insights. The analysis includes data cleaning, exploratory analysis, and visualizations.

## Data

The dataset contains information about bank loans, including customer details, loan characteristics, and repayment information. The key columns in the dataset are:

- `id`: Unique identifier for each loan
- `address_state`: State of the customer
- `application_type`: Type of application (individual or joint)
- `emp_length`: Length of employment
- `emp_title`: Job title
- `grade`: Loan grade
- `home_ownership`: Home ownership status
- `issue_date`: Loan issue date
- `last_credit_pull_date`: Last credit pull date
- `last_payment_date`: Last payment date
- `sub_grade`: Loan sub-grade
- `term`: Loan term
- `verification_status`: Income verification status
- `annual_income`: Annual income
- `dti`: Debt-to-income ratio
- `installment`: Monthly installment amount
- `int_rate`: Interest rate
- `loan_amount`: Loan amount
- `total_acc`: Total number of credit accounts
- `total_payment`: Total payment made

## Analysis

The analysis is divided into the following parts:

1. **Exploratory Analysis**: Exploring the dataset to understand the distribution of key variables and relationships between them and gain useful insights from them.
2. **Tableau Dashboard**: Creating visualizations to present the findings in an interactive manner.

## SQL Queries

The SQL script (`Bank_Loans_SQL_Script.sql`) contains queries used to analyze the dataset. Key queries include:

- Extracting loan distribution by state
- Analyzing the relationship between employment length and loan grade
- Calculating the default rate by loan grade

## Tableau Dashboard

The Tableau dashboard (`Bank_Summary_Dashboard.twbx`) provides an interactive visualization of the key insights. It includes charts and graphs that highlight important patterns in the data.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BankLoansAnalysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd BankLoansAnalysis
   ```

## Usage

1. Open and run the SQL script in the `analysis` folder to view the data exploratory analysis.
2. Open the Tableau workbook (`Bank_Summary_Dashboard.twbx`) to interact with the dashboard.

## Results

The analysis reveals insights into customer profiles, loan characteristics, and repayment behaviors. For detailed findings, refer to the Jupyter notebooks and Tableau dashboard.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.

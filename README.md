# Data Wrangling and Exploratory Data Analysis (EDA) of Prosper Loans data

# About the Loan Data from Prosper
Prosper is a peer-to-peer lending platform, where borrowers with fair or good credit can apply for loans and investors can fund them. To qualify applicants, Prosper uses a proprietary rating system that considers data points like credit history and debt-to-income ratio. Then, a prospective borrower is assigned a Prosper score, which investors use to decide whether to fund the loan.

When a loan is listed on the platform, it is open for funding by investors. Once a certain percentage of the loan amount has been funded by investors, the loan is considered "funded" and the borrower can access the funds. The loan application expires if the loan request isn’t at least 70% funded within 14 days, though most loans are funded within three days, according to the company. Source: nerdwallet.com

# Project tasks are split into 2:

## Preliminary Data Wrangling
The loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This [data dictionary](https://docs.google.com/spreadsheets/d/1djKkeentYxKqgNFO2ZHF-KFwVunoZ83VbyLyWYz82M8/edit?usp=sharing) explains the variables (i.e columns) in the data set.

For this project, focus will be on just 10 - 20 of the variables in the dataset to answer frequently asked questions like: What factors affect a loan's outcome status? What affects the borrower's interest rate or annual percentage rate (APR)? How do loans differ based on the size of the loan amount? These are some of the questions that I will attempt to answer in this project. But before any exploratory data analysis could be done, data wrangling/pre-processing was necessary to assess and clean up all quality and tidiness issues in the dataset.

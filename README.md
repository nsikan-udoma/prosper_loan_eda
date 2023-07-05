# <p align="center" style="margin-top 0px;"> 📊 Data Wrangling and Exploratory Data Analysis (EDA) of Prosper Loans data 💰  

<p align="center" style="margin-bottom: 0px !important;">
<img src="https://github.com/nsikan-udoma/prosper_loan_eda/blob/bee04481147088ae0291684941e37f6680cd689a/icons%20and%20images/Prosper%20EDA%20cover%20image.svg" width="960" height="540">

<br>

---
# About the Loan Data from Prosper
Prosper is a peer-to-peer lending platform, where borrowers with fair or good credit can apply for loans and investors can fund them. To qualify applicants, Prosper uses a proprietary rating system that considers data points like credit history and debt-to-income ratio. Then, a prospective borrower is assigned a Prosper score, which investors use to decide whether to fund the loan.

When a loan is listed on the platform, it is open for funding by investors. Once a certain percentage of the loan amount has been funded by investors, the loan is considered "funded" and the borrower can access the funds. The loan application expires if the loan request isn’t at least 70% funded within 14 days, though most loans are funded within three days, according to the company. Source: nerdwallet.com

---
## Available Data
  
 #### ``Snippet of Dataset``
ListingKey | ListingNumber | ListingCreationDate | CreditGrade | Term | LoanStatus  | ClosedDate  | BorrowerAPR  | BorrowerRate  | LenderYield  |  ...  | LP_ServiceFees  | PercentFunded  | Investors
-- | -- | -- | -- | -- | --  | --  | --  | --  | --  | --  | --  | --  | --
1021339766868145413AB3B	 | 193129 | 2007-08-26 19:09:29.263000000  |  C  |  36  |  Completed  |  2009-08-14 00:00:00  |  0.16516  |  0.1580  |  0.1380  |  ...  |  -133.18  |  1.0  |  258
10273602499503308B223C1	 | 1209647 | 2014-02-27 08:28:07.900000000	|  NaN  |  36  |  Current  |  NaN  |  0.12016  |  0.0920  |  0.0820  |  ...  |  0.00  |  1.0  |  1
0EE9337825851032864889A	 | 81716 | 2007-01-05 15:00:47.090000000  |  HR  |  36  |  Completed  |  2009-12-17 00:00:00  |  0.28269  |  0.2750  |  0.2400  |  ...  |  -24.20  |  1.0  |  41
0EF5356002482715299901A	 | 658116 | 2012-10-22 11:02:35.010000000	|  NaN  |  36  |  Current  |  NaN  |  0.12528  |  0.0974  |  0.0874  |  ...  |  -108.01  |  1.0  |  158



# Preliminary Data Wrangling
The loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This [data dictionary](https://docs.google.com/spreadsheets/d/1djKkeentYxKqgNFO2ZHF-KFwVunoZ83VbyLyWYz82M8/edit?usp=sharing) explains the variables (i.e columns) in the data set.

For this project, focus will be on just 10 - 20 of the variables in the dataset to answer frequently asked questions like: What factors affect a loan's outcome status? What affects the borrower's interest rate or annual percentage rate (APR)? How do loans differ based on the size of the loan amount? These are some of the questions that I will attempt to answer in this project. But before any exploratory data analysis could be done, data wrangling/pre-processing was necessary to assess and clean up all quality and tidiness issues in the dataset.

Visit the python notebook for [data wrangling steps](https://nbviewer.org/github/nsikan-udoma/prosper_loan_eda/blob/data_wrangling/notebook.ipynb).

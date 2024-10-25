Lending Club Case Study
Case Study: developing a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
  - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
  - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The objective is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

When a person applies for a loan, there are two types of decisions that could be taken by the company:
  - Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
      - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
      - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
      -  Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
  - Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Conclusions
 - the grade is B.
 - taking loans to clear other debts
 - having ownership of the house as Rent
 - loans are taken for interest rates of 10-20%
 - open credit lines in the borrower's credit file is 2-20
 - the amount of credit the borrower has used relative to all available revolving credit its very much likely by 40-100%.
 - annual income is between 31K - 58K
 - installments are 145-274. Higher the installments, more likely to default.
 - loan amounts applied for are really small, like, 5K-10K.
 - DTI is between 12-18.
 - loans applied for longer term of 36 months.
 - verification status is 'Not Verified'.
 - there are 0 inquiries in the last 6 months.
 - loan is issued during the last months of the year, say, December.
 - most defaulters are from the year of issue 2011.
 - home ownership is Mortgage type, and income is between 60-70K. Even though, fully paid and charged off loan statuses are going hand in hand. We cannot really categorize on this data.
 - loans are taken for home improvement, and have income in between 60-70K.
 - annual income is 112-140K, with loan amount of 15-17.5K
 - loan amount availed is 25-30K, with 16-17.5 interest rate.
 - loan taken for small businesses with an amount 14-15k.
 - loans are taken in the December month of the year in between 12-13K.
 - loans taken in the year 2011, in between amount of 12-13k.
 - loan taken between 17.5-20K by grade F.
 - loans taken with interest rates of 17.5-20%, for amounts between 25-35K.

## Technologies Used
Python 
Matplotlib
Numpy
Pandas
Seaborn

## Acknowledgements
This project was inspired by live session of upGrad on EDA
UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform

## Contact
Collaborated by [@RJ-1111] Rijumani Deka and Saad Teli

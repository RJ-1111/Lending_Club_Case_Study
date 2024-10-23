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
 - Smaller loan amounts are more likely to be defaulted
 - Loans takeen for shorter term of 36 months are generally more defaulted
 - Loans approved during the last months of the year are more defaulted
 - Significant number of defaulters are from 2011.
 - Loan who have house on mortgage are significantly high in number of defaulters
 - Loans for small businesses and home improvements are generally defaulted

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
Collaborated by [@RJ-1111] and Saad Teli

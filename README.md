# Lending Club Case Study
> In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## Table of Contents
* [Business Understanding](#business-understanding)
* [Business Objectives](#business-objectives)
* [Data Understanding](#data-understanding)
* [Project Information](#project-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## Business Understanding
> We work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

 - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
 - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


![Loan_image](./images/Loan_image.png)

> When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

    1. Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

    2. Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

    3. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Business Objectives
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

> Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

>If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

> In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Data Understanding
> We are using Loan Data Set. It contains the complete loan data for all loans issued through the time period 2007 to 2011.
> We are also referring the data dictionary which describes the meaning of these variables.

> The aformentioned files are present inside this repository as:
1. loan.csv
2. Data_Dictionary.xlsx

## Project Information
> Our EDA is divided into following parts:
- Data Understanding
- Data Cleaning and preprocessing
- Univariate Analysis
- Outliers Removal
- Segemented Univariate Analysis
- Bivariate Analysis
- Recommendations for Lending Club

## Technologies Used
- Python - version 3.8.8
- Numpy - version 1.20.1
- Pandas - version 1.2.4
- Matplotlib - version 3.3.4
- Seaborn - version 0.11.1


## Conclusions
- Lending Club should give loans to borrowers who has lesser debt to income ratio.
- Lending Club should try to grant loans for shorter terms.
- Lending Club should avoid borrowers with higher public bankruptcy records.
- Borrowers with higher public derogatory records are more likely to fully pay off their loans in order to improve their credit records.
- Lending Club should improve their verification process to avoid the chances of getting any charged off borrowers.
- Lending Club should target higher annual income borrowers. Because they take loan across all segments i.e. lower to higher loan amount.
- Borrowers who took loan for the purpose of 'small_business' had the highest percentage of total loans that were charged off.
- Borrowers with home_ownership as 'OTHER' were more likely to get charged off.

## Contact (GitHub)
Created by: 
- [Shubhanshu Kumar Singh](https://github.com/shubhanshu1995) 
- [Abhishek Kumar Goyal](https://github.com/akkgoyal)

## Connect with us on LinkedIn:-
- [shubhanshu001](https://www.linkedin.com/in/shubhanshu001/)
- [abhishek-k-goyal](https://www.linkedin.com/in/abhishek-k-goyal/)

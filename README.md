# Lending Club Case Study

## Problem Statement
Solving this Case Study will give you an idea about how real business problems are solved using Exploratory Data Analysis. In this case study, apart from applying the techniques will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to the customers.

## Business Understanding
- Here we have used loan.csv dataset in our project, loan data for all loans issued through the time period 2007 t0 2011.

- A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a  decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

  * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
  * If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
 
- When a person applies for a loan, there are two types of decisions that could be taken by the company:
  
  ### Loan accepted: 
  If the company approves the loan, there are 3 possible scenarios described below:
         * Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
         * Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
         * Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
  ### Loan rejected: 
  The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those         applicants with the company and so this data is not available with the company (and thus in this dataset)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Objectives

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Conclusions
- Higher the rate of interest more the chance of defaulting.
- Customer staying in rented or mortgage  house have high tendency to default.
- Customer with more bankrupt history have high tendency to default.
- When the purpose is debt consolidation check applicant thoroughly as it has high tendency to default.
- Higher interest rate loan has more defaulter. Always need to check the background of applicant thoroughly whenever interest rate is high.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3
- Numpy
- Pandas
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- References : https://www.kaggle.com/ekami66/detailed-exploratory-data-analysis-with-python


## Contact
Created by [@Akshu26] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

# Gramener-Case-Study
## Problem Statement
### Introduction
In this case study,after applying EDA(Exploratory Data Analysis) i need to have basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

### Business Understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision: <br />
  1.If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company <br />
  2.If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company <br />
 The loan data contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns      which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
 In this case study, i am using  EDA to understand how consumer attributes and loan attributes influence the tendency of default.
 
 ![loan_image](https://user-images.githubusercontent.com/42746311/51308684-acd3e680-1a68-11e9-838d-f24825a1de16.png)
 When a person applies for a loan, there are two types of decisions that could be taken by the company:<br />
  &nbsp; &nbsp; &nbsp; &nbsp; 1.Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:<br />
   &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp;1.Fully paid: Applicant has fully paid the loan (the principal and the interest rate) <br />
  &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp;2.Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.<br/>
  &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp;3.Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan <br />
  &nbsp; &nbsp; &nbsp; &nbsp; 2.Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
 

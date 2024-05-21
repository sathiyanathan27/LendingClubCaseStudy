# Lending Club Case Study

## Problem Statement

### Introduction
Solving this assignment will give you an idea about how real business problems are solved using Exploratory Data Analysis (EDA). In this case study, apart from applying the techniques you have learned in EDA, you will also develop a basic understanding of risk analytics in banking and financial services. This will help you understand how data is used to minimize the risk of losing money while lending to customers.

### Business Understanding
You work for a consumer finance company that specializes in lending various types of loans to urban customers. When the company receives a loan application, it has to decide on loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
2. If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The data provided contains information about past loan applicants and whether they defaulted or not. The aim is to identify patterns that indicate if a person is likely to default. This information can be used for taking actions such as denying the loan, reducing the loan amount, or lending to risky applicants at a higher interest rate.

### Business Objectives
The company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss, known as credit loss. Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In this case, customers labeled as 'charged-off' are the defaulters.

By identifying these risky loan applicants, the company can reduce the number of such loans, thereby cutting down the amount of credit loss. The identification of such applicants using EDA is the aim of this case study.

### Data Description
When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. **Loan accepted**: If the company approves the loan, there are three possible scenarios:
   - **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate).
   - **Current**: Applicant is in the process of paying the installments, i.e., the tenure of the loan is not yet completed. These candidates are not labeled as 'defaulted'.
   - **Charged-off**: Applicant has not paid the installments in due time for a long period, i.e., he/she has defaulted on the loan.

2. **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements, etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available.

### Aim
The company wants to understand the driving factors behind loan default, i.e., the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment. 

To develop your understanding of the domain, you are advised to independently research a little about risk analytics. Understanding the types of variables and their significance should be enough.


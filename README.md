# Loan Default Prediction Case Study
> This project explores how real business problems are solved using Exploratory Data Analysis (EDA). It focuses on developing a basic understanding of risk analytics in banking and financial services, specifically how data is used to minimize the risk of losing money while lending to customers.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Project Background:** This project is designed to give insights into solving real business problems using EDA techniques. It also aims to develop an understanding of risk analytics in the banking and financial services sector.
- **Business Problem:** The project focuses on a consumer finance company that specializes in lending various types of loans to urban customers. The main challenge is to make informed decisions about loan approvals based on applicants' profiles. The two primary risks are:
  - Loss of business if a loan is not approved to an applicant who is likely to repay.
  - Financial loss if a loan is approved to an applicant who is likely to default.
- **Dataset:** The dataset contains information about past loan applicants and whether they defaulted or not. The goal is to identify patterns that indicate if a person is likely to default. This information can be used to make decisions such as denying the loan, reducing the loan amount, or lending at a higher interest rate to risky applicants.

## Conclusions
- After univariate analysis, we derived 10 driver variables - indicators for loan default
- Bivariate analysis is performed to identify relationships between:
  1. pub_rec and pub_rec_bankruptcies
  2. Grade and sub_grade
- From this analysis, we derived 8 driving factors for loan default.

### Derived Variables
| Variable             | Variable Type          |
|----------------------|------------------------|
| term                 | Ordered Categorical    |
| int_rate             | Ordered Categorical    |
| sub_grade            | Unordered Categorical  |
| annual_inc           | Numerical              |
| verification_status  | Unordered Categorical  |
| purpose              | Unordered Categorical  |
| pub_rec              | Numerical              |
| revol_util           | Numerical              |

## Technologies Used
- **Python:** 3.11.7
- **Pandas:** 2.1.4
- **NumPy:** 1.26.4
- **Matplotlib:** 3.8.0
- **Seaborn:** 2.1.4

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).

## Contact
Created by [@sathiyanathan27] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->



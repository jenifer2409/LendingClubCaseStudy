# Lending Club Case Study
Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

## General Information
- Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile.
- Identify risky loan applicants. Such loans can be reduced thereby cutting down the amount of credit loss.

### Business Objective¶
The dataset we have been given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of the loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, we will use Exploratory Data Analysis to understand how consumer attributes and loan attributes influence the tendency of default.

### Technical Objective
To use Exploratory Data Analysis (EDA) to understand how consumer attributes and loan attributes influence the tendency of default. From the insights identified, we will provide recommendations on what attributes can be considered to reduce loans that result in credit loss.

### Steps Followed in our EDA
Data Sourcing
Data Cleanup
Data Understanding
Univariate Analysis
Bivariate Analysis (Includes analysis using Derived Metrics)
Multivariate Analysis

### Disclaimer:
Do execute our code file, dataset loan.csv should be placed in the same location as the code file.

## Technologies Used
- Python
- Numpy
- Pandas
- matplotlib
- seaborn
- plotly
- missingno

## Conclusions
- Larger loan amounts (> 15000) for a 60-month term across high-risk grades (D to G) must be given with caution.​
- In general, small business loans are charging off at a high rate - these loans have to be given out with caution considering these additional variables - Loan amount taken between 10k to 35k, for a 60-month term with interest rate > 9%.​
- Higher loan amounts (>20k) having higher dti (>16) must be given out with caution.​
- Educational and housing loans taken at a 60-month term with an interest rate >15% must be given out with caution.​
- People with annual income between 20k to 60k taking loans more than 15k at higher interest rates (>17%) tend to have higher dti (>10 - these are high-risk loans) and must be considered with caution.​
- High-risk loans with grades E,F,G charge off more than 30% and must be given out with caution.​
- Loans given out in NV state must be considered with caution.​
- Although we do not have sufficient data on borrowers with a previous record of bankruptcies, from the available dataset, it can be seen that people with a previous record of bankruptcies tend to default again. These loans must be given with less priority.

## Contact
- Chethana Manyam​
- Jenifer Sam​
- Pallavi Nigam 

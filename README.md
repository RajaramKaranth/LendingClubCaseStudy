# Lending Club Case Study
A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

In this analysis, EDA is used to understand how consumer attributes and loan attributes influence the tendency of default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


Aim of this case study is to use EDA over the dataset containing the complete loan data for all loans issued through the time period 2007 to 2011  and assess the driving factors behind the loan default. such that the company can utilise this knowledge for its portfolio and risk assessment. 

In this analysis, EDA is used to understand how consumer attributes and loan attributes influence the tendency of default.


## Technologies Used
- Python - version 3.10.9
- IPython - version 8.10.0
- pandas - version 1.5.3
- numpy - version 1.23.5
- seaborn - version 0.12.2
- jupyter notebook - version 6.5.2


## Conclusions
- Maximum number of loans taken are for the purpose of debt consolidation. More chances of default in this category as this option just provides breathing time for otherwise a possible delinquent loan in the previous institution
- Most number of  loans are issued in big cities
- Number of open credit lines has a positive correlation with delinquency although not very strong. However more number of open credit lines increases the risk profile of the customer.
- In the given dataset, dti is found to be lower in the delinquent cases. 
Lower dti is a strong indicator of a possible default as it indicates lower debt repayment capacity of the borrower.
- Months since delinquency is inversely correlated with the repayment. recent delinquencies indicates chances of default
- Maximum number of charged off loans for the purpose of debt consolidation are of grade B.
More caution to be exercised on the loan applications with these attributes 
- The currently running loans have the Median value for Revolving utilization is very near to the Median of Charged off loans. This is a strong indicator of possible default.


## Acknowledgements
Give credit here.
- This project was based on the learnings from EDA module of ML C54 EPGP program by IIIT Bangalore and upGrad


## Contact
Created by [@githubusername] - feel free to contact me!



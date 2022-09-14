# Lending Club Case Study
## Objective
This case study is for a lending company, which is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. We will perform EDA to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.

## Steps for the case study
1. Data cleaning
2. Data preparation and wrangling
3. Univariate analysis
4. Bivariate analysis
5. Correlation study
6. Final observations

## Univariate Analysis Conclusions
Applicants are likely to default on lending when:
- Applicants who show the below characteristics are most likely to default on lending:¶
- Employment length of more than 10 years
- Interest rate between 13%-16.99%
- Installment amount less than 250
- Grade is B and Sub grade is 5
- Stays in rented accomodation
- Annual income between 27200 and 50400
- Accounts that are not verified
- Accounts that have taken loan for the purpose of Debt Consolidation
- People from California state
- Loans that were issued in Dec 2011
- Customers who have relatively newer credit line history of less than 10k days
- DTI between 12 and 18
- The number of 30+ days past-due incidences of delinquency in the borrower's credit file for the past 2 years is less than 2
- Inquiry in last 6 months is less than 20
- The number of open credit lines in the borrower's credit file is less than 10
- Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit is between 60 and 80
- Total number of credit lines in account is less than 20
- Loan term is 36 months

## Bivariate Analysis Conclusions
Applicants are likely to default on lending when:
- When employment length is 10 years and higher and loan amount between 12000 & 14000
- When purpose is small_business and loan amount is greater than 14000
- When home ownership is mortgage and loan amount is between 12000 and 14000
- When the loans were issued in December of 2011
- When grade is F and loan amount between 17500 and 20000
- When verification status is verified and loan amount between 14000 and 16000
- When annual income is higher than 60000 and purpose is home improvement
- When annual income is between 60000 and 80000 and home ownership is Mortgage
- When annual income is between 95000 and 12000 and loan_amount is more than 17500
- When annual income is between 60000 and 70000 and interest rate is between 21-24%
- When loan_amount is between 17500 and 20000 and interest rate is between 21-24%
- When interest rate is between 14-16% and term is 60 months
- When annual income is 50000-60000 and term is 60 months
- When loan_amount is 14000-16000 and term is 60 months

## Correlation Map Conclusions
- Fields loan_amnt, funded_amnt, funded_amnt_inv and installment are highly correlated
- These fields are proportional to each other
- Also the public records related fields pub_rec & pub_rec_bankrupcies
- Number of accounts related fields open_acc & total_acc are correlated

## Contact
Created by https://github.com/abhi30051990 - feel free to contact me!



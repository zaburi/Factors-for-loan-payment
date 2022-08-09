# Loan Data from Prosper Exploration
## by Zaburi Frolian Mwachusi


## Dataset
This data set contains 113,937 loans with 81 variables on each loan, 
including loan amount, borrower rate (or interest rate), current loan status, 
borrower income, and many others. 
The dataset can be found here (https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)



## Summary of Findings

In the exploration, I found that there is strong relationship between the ability to pay the loan(loanstatus-'Completed') 
and the income range. This is one of the feature that show much of relationship 
but on top of that there is also the employment status and employment status duration 
they play a vital role in determining the capabilities of individual to pay the loan. 
Property ownership is one of the feature used by most of financial institutions 
as collateral to offer the loan as they anticipate for payment, 
but data showed most of loans payed were from people who are not home owners. 
This can validate that Cashflow is what's important to determine payments

Other Categorical features include areas where the borrowers come from. 
With 61,311 US dollars GDP per capita Colorado had highest number of completed loans 
together with current loans. California and Newyork also have considerable amount of loans 
that are completed. These are busy stated with much of economic activities 
which can ensure cashflow to their individual

## Key Insights for Presentation

For the presentation, I focus on just few features that were the main key of my investigation 
I will start with the numerical features as I believe these are the most import which 
also determine the influence of other features 

Afterwards, I will introduce categorical features and explain there influence one by one. 
I will explain their influence together with some of the numeric features. 
I will use mostly bar charts together with heatmaps. 
I did my best to use headings and small things such as legends  
that will give a clue to understand a trend and clear picture from the plots
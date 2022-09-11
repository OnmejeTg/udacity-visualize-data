# (How Various loan data features affect borrowers APR)
## by (ThankGod Onmeje)


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, 
borrower rate (or interest rate), current loan status, borrower income, and many others. 
The loans were given by proser loan company and can be downloaded from 
[here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)
The data dictionary can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Summary of Findings

In this exploration I found that there is a strong negative corrolation between
the BorrowersAPR and the Proser Score ie. the higher the prosper score the lower 
the APR. Also that the higher the loan amount the lower the borrowersAPR showing a negative 
corrolation between the two

Outside the main variable of interest I found that there exist a strong positive corrolation
between the monthly income and loan amount which makes sense because the more the money 
a person earns the more amount of loan he is allowed to take. 

## Key Insights for Presentation

For the presentation, I focus on what features affect the borrowersAPR and how it 
affects it. I started by extracting the features that I suspect would affect the 
borrowersAPR and then explored the various individual features using a bar chart 
for the categorical varibles ans a histogram for the numerical variabes and finally plotted 
how each vaiables affected the variable of interest.
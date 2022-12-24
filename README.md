# Prosper Loan Data Exploration
## by Joseph Stanley

## Introduction
This data set contains 113,937 loan listings by a loan company Prosper with 81 variables on each loan which are uniquely identified by a listing Key and are stored on Udacity's server.  
These loan variables include:
* The loan amount.
* The borrower rate (or interest rate).
* The status of the loan.
* Each borrower's stated monthy income and many others available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).



## Summary of Findings

* Most of the loans listed in the timeframe were currently being serviced then with about 38,000 loans already completed with 77% of them listed on 36 month Terms.
* A very large fraction of the loans (close to 60,000) were obtained for debt consolidation and most of the loans were given out in multi thousand Dollar round figures.
* The average borrowers APR(Total annual  to be payed by borrowers in percentage) had a normal distribution that is skewed to the right with a mode at around 0.36%.
* The top 10 borrowers were mostly corporate workers while least loan takers were students at different levels.
* The average ststed income for the borrowers was about 5,000 dollars with a significant number of borrowers stating 0USD as their monthly income.
* loans with Positive Estimated returns loans were very inclusive of low risk borrowers as well as high risk borrowers while the Negative return loans were always associated with very high risk borrowers.
* Loans given out in higer amounts were oftentimes assigned lower annual payment rates.
* High risk borrowers were often tasked with higher APRs.
* Loan terms were mostly not related to the risk factors, Estimated yield or APR but just slightly postively dependent on the loan amount.
* Almost all borrowers regardless of Employment status often times preferred taking longer term loans with most of the loans falling in the 36 month term category. Retired borrowers and part-time employed borrowers also had a very stong affinity for 60 months loans.

# [SUMMARY REPORT](https://github.com/stanleyjoe33/Prosper-Loans-Data-Analysis/blob/d5287d1023fa4769fcb01cedc49a9139c36b5010/Prosper%20Loans.pdf)

## Key Insights for Presentation
For the presentation, I  would focus mainly on the apparent lending patterns of the company and how these may be related to peculiarities discovered in borrower profiles. I would start by introducing the distribution of their loan listings as per status, Listing category (reason for the loan) and Loan Terms followed by important variables regarding borrower profiles like their Employment status and Borrowers' APRs.
To check for relationships, the prosper rating which is the company's risk analysis of the borrowers would  be examined with reference to their Estimated Returns for those that have  Negative and  Postive values respectively. 
Finally a Facet Grid of Loan Amount vs Borrower APR by Loan Term and Employment Status to show how these four variables interact.

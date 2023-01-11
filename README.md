# Prosper Loan Data Exploration
## by Joseph Stanley

## Introduction
The data set contained 113,937 loan listings by a loan company Prosper with 81 variables on each loan which were uniquely identified by a listing Key and are stored on Udacity's server.  
These loan variables include:
* The loan amount.
* The borrower rate (or interest rate).
* The status of the loan.
* Each borrower's stated monthy income and many others available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).
## Summary of Methodology

The investigation was focused on determining the extent to which the company's loan amounts were correlated with borrower characteristics, such as credit score, employment status, and other risk factors. The data consisted of 118,000 loan listings, which were first cleaned and classified by loan status, listing category, and loan terms. Additionally, variables regarding borrower profiles, including employment status and borrower APRs, were extracted for analysis.
To examine the relationships between these variables, the company's own risk analysis of the borrowers, known as the Prosper Rating, was analyzed in relation to the estimated returns for borrowers with positive and negative values. Finally, a facet grid was created to display the interaction between loan amount, borrower APR, loan term, and employment status.
Overall, data analysis was employed to understand the factors that influence the company's loan decisions and assess any potential correlations with borrower characteristics."



##  Summary of Findings:

* Most of the loans listed in the timeframe were being serviced at the time of analysis, with around 38,000 loans already completed, the majority of which had 36-month terms.

* A significant portion of the loans (nearly 60,000) were obtained for debt consolidation, and many of the loans were given in round-figure dollar amounts.

* The distribution of average borrower APRs was skewed to the right, with a mode around 0.36%.

* The top 10 borrowers were mostly corporate workers, while students at various levels were among the least likely to take out loans.

* The average stated income for borrowers was around $5,000, but a significant number of borrowers stated $0 as their monthly income.

* Loans with positive estimated returns included both low-risk and high-risk borrowers, while negative return loans were associated with very high-risk borrowers.

* Loans given in higher amounts were often assigned lower annual payment rates.

* High-risk borrowers were often assigned higher APRs.

* Loan terms were only slightly positively correlated with loan amount and not significantly related to risk factors, estimated yield, or APR.

* Most borrowers, regardless of employment status, preferred longer-term loans, with the majority falling into the 36-month category. Retired borrowers and part-time employed borrowers also showed a strong preference for 60-month loans.


## Key Insights for Presentation
For the presentation, I focused on the apparent lending patterns of the company and how these may have  been related to peculiarities discovered in borrower profiles. I will began by introducing the distribution of the company's loan listings according to status, listing category (reason for the loan), and loan terms.

Next, I  examined variables related to borrower profiles, such as employment status and borrowers' annual percentage rates (APRs), and how they affected the company's lending patterns.

To further investigate any potential relationships, I  analyzed the Prosper rating, which was the company's risk assessment of the borrowers, in relation to the estimated returns for borrowers with negative and positive values, respectively.

Finally, I  presented a facet grid showing the interaction between loan amount, borrower APR, loan term, and employment status. This  provided a visual representation of how these variables might have affectrd each other.
 

## [ CLICK FOR SUMMARY REPORT PRESENTATION](https://github.com/stanleyjoe33/Prosper-Loans-Data-Analysis/blob/d5287d1023fa4769fcb01cedc49a9139c36b5010/Prosper%20Loans.pdf)


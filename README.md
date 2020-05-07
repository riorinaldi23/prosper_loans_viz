# prosper_loans_viz
A data visualization project using loan data from Prosper (a peer-to-peer lending platform). Part of Udacity's Data Analyst Nanodegree

# How Do You Get a Low APR on a Loan? Exploring Borrower's Profile from a Peer-to-Peer Lending Platform
## by Rio Rinaldi


## Dataset

The Prosper dataset contains data of borrower profiles as well as their loan application. It contains an exhaustive list of information, ranging from income level, house ownership, employment status, credit limit, as well as information on the loan, such as the term, APR, estimated loss and gain, and many others.


## Summary of Findings

### Univariate Exploration

We found that the data contained almost an equal proportion of borrowers that owned homes and did not. We also found that borrower's APRs peaked around 10 - 15 percent, with another peak at 35 percent. We also debt-to-income ratios had outliers at around 1000 percent, in which we decided to not use those as to reduce the skewness of our results. Log transformation did help but it was still too severe. We also found that the majority of loan term lengths was 36 months, and as expected, Prosper's internal scoring system was highly correlated with the borrower's APR.

### Bivariate Exploration

We found that, in general, the higher risk profile you are, the higher your APR. This applied to income, with the exception of $0 income which is not clearly defined but if we had to guess would be students or the like. The general principles also applied to debt-to-income ratio, and employment status. 


## Key Insights for Presentation

We saw a weak relationship that being a homeowner actually slightly increases your APR, given debt to income ratio. However, this is likely because people that have a lot of debt tend to be homeowners. I thus recreated the graph but only looking less than 50 percent Debt to Income Ratio and found that the relationship weakened. Thus, we don't really see that homeownership combined with debt to income ratio impacts APR much.

For employment status and loan term length, it looks like if you are not high risk, then a shorter term length means lower APR (being employed and full-time). However, if you are high risk, a short term loan gives higher APR. This makes sense, given that you become much higher risk for lenders.

For income and homeownership, we saw a clear relationship. We found that having a home is a valuable asset and on average, does reduce your APR. This applies for all income levels except if you are unemployed, in which maybe having a home can be seen as risk because you have to continue paying mortgage payments or risk losing the house.

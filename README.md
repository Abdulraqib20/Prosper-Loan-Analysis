# (Exploration of Loan Data from Prosper)
## by (Abdulraqib Omotosho)


## Dataset

The dataset I will be exploring and visualizing for this project is the [Loan Data from Prosper](https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1676827485502191&usg=AOvVaw1C3wctFYsHg01Gb5Eopirm) gotten from Udacity's curated datasets.
This dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

## Summary of Findings

For this project, my main task was to explore the features related to the borrowers and how it relates to the loans they took. <br>
I started off with the univariate exploration where I explored the distribution of individual features. I got some notable insights from this exploration such as the majority of borrowers originating from California. I also observed that most borrowers are either employed or Full-time. A little minority took their loans for a year while most took their for 36 months.Exploring the Listing Category further, majority of the loans was tajen for Debt consolidation. Taking a look at the ProsperLoans score, it can be seen that most borrowers have a not so good risk score of 4.0. <br><br>
Next I moved on to the Bivariate exploration where I investigated relationships between pairs of variables in the dataset. Using a heatmap, I explored the correlation of all numeric variables in the data and found out that BorrowerAPR and BorrowerRate are highly correlated. Looking down the chart, I observed Investors have a correlation of 0.38 with LoanOriginalAmount. I also observed that borrowers with the highest monthly income took the least number of loans while those
with the most loans taken are the low income earners. Exploring further, TotalProsperLoans is negatively correlated with StatedMonthlyIncome. Most borrowers also took loans in the month of May while very few loans were taken at the end of the year. <br><br>
Next, I moved on to the Multivariate exploration where I created plots of three or more variables to investigate the data even further. I used plot matrices to investigate the relationship between numeric features and categorical features in the data. I noted that IncomeRange and LoanOriginalAMount are positively correlated. I then checked the relationship between TotalProsperLoans and StatedMonthlyIncome based on BorrowerRate. Here, I observed that borrowers with the least number of loans taken are the highest earners and they also have the highest interest rate (BorrowerRate). I also noted that the more you take loans, the higher your interest rate(safe for the borrowers who took a single loan). Exploring the data further, I reviewed the relationship between Employment status and Loan Amount for Home-owners and non Home-owners. I found out that Borrowers who are either employed or Full-time and are home-owners tend to have more loan original amount. Also, self-employed borrowers who are home owners tend to have much loan original amount. An interesting interaction I noticed was that folks who have a larger Income range tend to have the larger amount of loan original amount. <br>
Finally, it was fun making this analysis and applying what I have learnt from the Data Visualization course of the Data Analyst Nanodegree to this exciting project. One issue I faced though was picking the best features from the many variables in the dataset for this analysis.


## Key Insights for Presentation

For the presentation, my objective focused on the exploration of the individual features of interest to discover the relationship between the borrowers and the loans they took and other correlations between various variables in the dataset.

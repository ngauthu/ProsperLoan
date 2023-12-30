# ProsperLoan
Visualization of private loans and factors impacting returns on loans
_Ngau-Thu Nguyen_

## Dataset Overview 

> The dataset is provided by Udacity on Prosper loan, including 113 937 observations, each corresponds to a loan profile, and 81 columns, each corresponds to a characteristics of a loan such as loan terms and loan statuses.There are quite many columns, and in this project I only use a subset of columns of interest.

## Summary

> There are 2 parts to this analysis: exploration and explanatory presentation.
The data analysis gives us confirmation on the concept of higher risks, higher returns. 
There is a positive relationship between the debt-to-income ratio and the estimated effective yield/ APR.
The boxplot and violin plots also indicate that the higher the loan term becomes, the higher the estimated effective yield gets. 
The estimated effective yield is lower on average when income is verifiable.
The estimated effective yield is lower on average when the borrower is a homeowner. The original loan amount is higher on average when the borrower is a homeowner.
When we look at the violin plot, as the borrower's rating improves, the estimated effective yield decreases significantly. We also see that the estimated effective yield is the highest among the worse loan profiles (defaulted and charged off, past due) on average.
When we move to multivariate explorations, we can see that loan term can have an effect on the relationship between loan original amount and estimated effective yield. There is a stronger relationship between loan original amount and estimated effective yield when loan term is 36 or 60 months. However, loan term does not seem to have a clear impact on the relationship between debt-to-income ratio and estimated effective yield.

## Insights for the explantory presentation

> For the slidedeck presentation, I focus on a few insights below:

> 1. Distribution of estimated effective yield

> 2. Relationship between selected numeric variables in the dataset

> 3. Effect of employment status on the relationship between original loan amount and estimated effective yield

> 4. Effect of prosper rating on the relationship between original loan amount and estimated effective yield

> 5. Estimated Effective Yield across terms and ratings

## Licensing and Acknowledgements

>This project is part of the Nanodegree Data Analyst program I participated at Udacity. The dataset is provided by Udacity as one option to demonstrate the visualization skill as an important aspect of data analysis and communication.

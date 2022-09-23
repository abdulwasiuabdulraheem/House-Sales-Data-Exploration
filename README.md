# House Sales Data Exploration
## by Abdulwasiu Abdulraheem


## Dataset

This dataset consist of information regarding 21613 house sale prices for King County, including price, square footage, bathrooms, grade, overall condition and other house qualities. The dataset can is saved on IBM cloud:
'https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/data/kc_house_data_NaN.csv'


## Summary of Findings

In the  exploration, I found that the square footage  of the house has the strongest relationship with price. The relationship between these variables is positive and I was able to see it more clearly after a log transformation was performed on both variables, and transparency and jitter employed on the plot to make their scatterplot more informative.

I also found that increased house condition has a positive effect on price when I plotted waterfront, grade and condition on price. Among the 3 categorical features, I found that grade has a more stronger relationship with price.

I extended the investigation of price against square footage size to include condition to observe the role the overall condition of the house play in the relationship between price and square footage. The multivariate exploration revealed that there indeed is a positive effect of increased house condition on house price.


## Key Insights for Presentation

For the presentation, I focus on just the influence of square footage on house sale prices. I start by introducing the
price variable, followed by the pattern in square footage distribution, then plot the transformed scatterplot.
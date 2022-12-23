# House Sales Data Exploration
## by Abdulwasiu Abdulraheem


## Dataset

This dataset consists of information regarding 21613 house sale prices for King County, including price, square footage, bathrooms, grade, overall condition, and other house qualities. The dataset is saved on the IBM cloud:
'https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/data/kc_house_data_NaN.csv'


## Summary of Findings

In this exploration, the square footage of the house is found to have the strongest relationship with the house price.

The relationship between these variables is positive, and I was able to see it more clearly after a log transformation was performed on both variables, and transparency and jitter were employed on the plot to make their scatterplot more informative.

A better house condition is also found to have a positive effect on price when waterfront, grade, and condition are plotted against price. Grade has a stronger relationship with price than the other two categorical features.

The investigation of price against square footage is extended to include condition to observe the role the overall condition of the house plays in the relationship between price and square footage. The multivariate analysis revealed that improved house condition has a positive effect on house price. 


## Key Insights for Presentation

For the presentation, I focus on just the influence of square footage on house sale prices. I start by introducing the
price variable, followed by the pattern in square footage distribution, and then plot the transformed scatterplot.

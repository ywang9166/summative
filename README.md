# Summative Assignment Overview

This python code was for a data analytics and modelling assignment using the Lending Club loan dataset to investigate factors influencing interest rate determination. The report is divided into four parts.

Part A

The analysis begins with data cleaning, resulting in a dataset of over 10,000 observations and 15 selected variables relevant to borrower characteristics and loan terms. 

Part B

In the exploratory data analysis (EDA) phase, summary statistics are presented for key numerical variables — interest rate, annual income, debt-to-income ratio, and loan amount—along with frequency distributions for categorical variables such as loan grade, verified income status, and homeownership. 

The visualisation section uses histograms, scatterplots, and boxplots to explore key relationships in the data. It highlights how interest rates vary with income, debt levels, loan grade, income verification, and homeownership. These patterns support the selection of relevant variables for regression analysis.

New variables, including credit utilisation and bankruptcy dummies, are created to provide clearer insights and increase the analytical value of the dataset used in the regression models.

Part C

A series of linear regression models are developed to investigate the determinants of interest rates. Starting with simple regressions using single predictors like debt-to-income ratio and bankruptcy status, the analysis progresses to multiple and enhanced models incorporating both continuous and categorical variables. Dummy variables are created for factors such as verified income, grade, homeownership, and loan purpose. The most comprehensive model includes key borrower characteristics and loan details to better explain variations in interest rates, with residuals computed to assess model fit.

Part D

Finally, the code tests the limitations of Model 5, including the histogram of residuals, the comparison between homoskedastic and heteroskedastic robust standard errors, and the interaction terms. This helps to present a critical discussion of the model’s limitations, such as potential omitted variable bias, linearity assumptions, and multicollinearity. Recommendations are offered for model improvement, including log transformations, interaction terms, and the inclusion of additional relevant predictors. The economic implications of these enhancements are also discussed, with a focus on supporting more effective and data-driven credit risk assessment and interest rate setting by lenders.

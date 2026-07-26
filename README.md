# Customer Monthly Charge Multiple Linear Regression Analysis

## Overview
This project investigates which customer and service-related factors significantly influence monthly charges. A multiple linear regression model was developed in Python using Ordinary Least Squares (OLS) to identify the strongest predictors of customer monthly billing.

## Business Question
Which customer and service-related factors significantly influence MonthlyCharge?

## Dataset
- Customer Churn Dataset
- Response Variable:
  - MonthlyCharge
- Predictor Variables:
  - Bandwidth_GB_Year
  - Income
  - Tenure
  - Population
  - Children
  - Contract
  - InternetService
  - Phone
  - StreamingTV
  - StreamingMovies
  - TechSupport
  - OnlineSecurity
  - Area

## Tools
- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

## Statistical Method
- Multiple Linear Regression
- Ordinary Least Squares (OLS)

## Results
The regression model identified several customer and service characteristics that significantly influenced monthly charges. Variables including bandwidth usage, internet service type, streaming services, technical support, online security, and contract type were found to be important predictors of pricing.

## Conclusion
The analysis demonstrates that customer service selections and usage patterns are strongly associated with monthly charges. These insights can support pricing strategy, revenue forecasting, and customer segmentation. While the regression model identifies statistically significant relationships, it does not establish causation.

## Recommendations
The company should consider using these findings to:

- Improve pricing strategies.
- Enhance revenue forecasting.
- Develop targeted service bundles.
- Identify pricing opportunities for different customer segments.
- Support customer retention initiatives.

## Project Files

- [View the Jupyter Notebook](customer_monthly_charge_linear_regression.ipynb)
- [View the Full Written Report](LinearRegressionChurnModel.pdf)

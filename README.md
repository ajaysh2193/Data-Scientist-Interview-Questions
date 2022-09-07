# Data-Scientist-Interview-Questions

- How to test whether model is overfitting or underfitting?
- Explain PCA.

- What are the assumptions of Linear and Logistic Regression.
<br>Logistic regression does not require a linear relationship between the dependent and independent variables.  Second, the error terms (residuals) do not need to be normally distributed.  Third, homoscedasticity is not required. Fourth, the independent variables should not be too highly correlated with each other.  Finally, the dependent variable in logistic regression is not measured on an interval or ratio scale.<br>
Linear Regression Assumptions- 
<br> Linear relationship: relationship between the independent and dependent variables to be linear. LR is sensitive to outliers
<br> Multivariate normality: linear regression analysis requires all variables to be multivariate normal.  This assumption can best be checked with a histogram, Q-Q-Plot or K-S Test.
<br> Homoscedasticity: The last assumption of the linear regression analysis is homoscedasticity.  The scatter plot or Goldfeld-Quandt Test is good way to check whether the data are homoscedastic (meaning the residuals are equal across the regression line.
<br> No auto-correlation
<br> No or little multicollinearity: Multicollinearity may be tested with three central criteria:
1) Correlation matrix – when computing the matrix of Pearson’s Bivariate Correlation among all independent variables the correlation coefficients need to be smaller than 1.
2) Tolerance – the tolerance measures the influence of one independent variable on all other independent variables; the tolerance is calculated with an initial linear regression analysis.  Tolerance is defined as T = 1 – R² for these first step regression analysis.  With T < 0.1 there might be multicollinearity in the data and with T < 0.01 there certainly is.
3) Variance Inflation Factor (VIF) – the variance inflation factor of the linear regression is defined as VIF = 1/T. With VIF > 10 there is an indication that multicollinearity may be present; with VIF > 100 there is certainly multicollinearity among the variables.
4) Pertubation Testing

- How to find important features in dataset?
- How to find whether features or variables are independent or not?
- How to detect outliers in dataset
- Data Cleaning and Data Preprocessing Techniquess
- Performance Metrices and Cost Functions
- NLP Pipeline: ![nlp-pipeline](https://user-images.githubusercontent.com/24571705/51478253-f0a05600-1db0-11e9-9e7f-151aca73c5e6.png)
- Time Series Forecasting

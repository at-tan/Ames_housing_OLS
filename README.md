# Ames_housing
Linear regression modelling of the Ames housing dataset (2011), with the chief goal of predicting the house sale price. I used a log-linear model, and was guided by the hedonic pricing method to analysing house prices. The OLS model achieved rather stable results and scores, with the OLS coefficients and test scores (R-squared, MSE & RMSE) effectively matching those derived from the Ridge and Lasso regressions. 

The assorted property size variables, namely internal living area, basement finished area, lot area and garage area, were all found to be positively correlated to the sale price, and statistically significant. Build quality and condition were also found to be among the most important determinants of house prices, as was location desirability. The use of highly interpretable linear models allows for the simultaneous pursuit of prediction and statistical inference. The overall model and effects of individual variable may be easily communicated to non-technical audiences.

A description of the research methodology and the model findings are presented in https://towardsdatascience.com/wrangling-through-dataland-modeling-house-prices-in-ames-iowa-75b9b4086c96

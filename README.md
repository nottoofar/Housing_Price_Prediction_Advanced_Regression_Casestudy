# Lending Club Case Study
## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

## Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Approach

- Load the Data
<br>

- Data Inspection & understanding
    - Go through the Data dictionary, observe data values, study data segments
<br>


- Initial Data cleaning
    - Remove columns which are invalid, has high percentage of null data etc
    - Remove rows with high null data
    - Fix data types, suffixes and prefixes etc.
    - Outlier treatment
<br>


- Data Analysis
    - Univariate Analysis
    - Segmented Univariate Analysis
    - Bivariate/Multivariate Analysis
<br>


- Split Train-Test data sets
<br>


- Data cleaning
    - Handle missing Values ( eg:- Imputations)
<br>


- Data preparation for modeling
    - Transformation of Target Variable
    - Scale the features
<br>


- Feature Selection
    - Use RFE filter and select features
<br>


- Linear Regressions - Regularization & Model Evaluation
    - Ridge Regression
    - Lasso Regression
    - Model coefficients comparison
    - Model Evaluation
<br>


- Recommendations
    - Identify major variables which influence the price of a house to provide recommendation to predict the actual value of the prospective properties.

## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.0.5
- seaborn - version 0.11.2
- matplotlib - version 3.5.2
- statsmodels - version 0.11.1
- scikit - version 1.1.2


## Contact
Created by [@nottoofar] - feel free to contact me!


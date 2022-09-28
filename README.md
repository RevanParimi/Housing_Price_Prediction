# Project Name
> Outline a brief description of your project.


## Table of Contents
* Checking for Duplicates
* EDA
* Drop columns that are correlated and not contributing to 'SalePrice'
* Data Preparation
* Creating Dummy columns to convert categorical into numerical
* Model Building and Evaluation - Linear Regression, Lasso and Ridge Regression


## General Information
- We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- The company wants to know:

  a. Which variables are significant in predicting the price of a house, and

  b. How well those variables describe the price of a house.


## Conclusions

- Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house. The higher values of positive coeeficients suggest a high sale value.

- Some of those features are:-

- Feature Description

  1. GrLivArea Above grade (ground) living area square feet

  2. OverallQual Rates the overall material and finish of the house

  3. OverallCond Rates the overall condition of the house

  4. TotalBsmtSF Total square feet of basement area

  5. GarageArea Size of garage in square feet

- The higher values of negative coeeficients suggest a decrease in sale value.

- Some of those features are:-

  1.  PropAge Age of the property at the time of seeling

  2. MSSubClass Identifies the type of dwelling involved in the sale



## Technologies Used
- numpy
- pandas
- sklearn.linear_model - LinearRegression
- sklearn.linear_model - Ridge
- sklearn.linear_model - Lasso
- sklearn.model_selection - GridSearchCV
- sklearn.preprocessing - PolynomialFeatures
- sklearn.linear_model - LinearRegression


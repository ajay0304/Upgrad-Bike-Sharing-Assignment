# Bike Sharing Assignment

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

<br>

## Problem Solving Methodology
* Data Understanding-
> Understanding and working with data dictionary and getting good knowledge of all the columns and their domain specific uses.
* Data Cleaning-
> Removing null valued columns, single uniques columns, unnecessary columns then manipulation of data such as conversion of data types, deriving new variables and many more.
* Splitting the Data into Training and Testing Sets-
> The dataset is split into training and testing sets using train_test_split(). This ensures that the model can be evaluated on unseen data (test set) after being trained on the training set
* Building a Linear Regression Model
> A Linear Regression model is trained using the LinearRegression() class from Scikit-learn, with cnt as the target variable and the other features as independent variables. This model predicts the bike-sharing demand.
* Making Predictions-
>The model makes predictions on the test set using model.predict(X_test). These predictions are later used to evaluate the model's performance
* Evaluating the Model with R-squared-
> The performance of the model is evaluated using the R-squared score (r2_score), which indicates how well the model fits the data. The closer the R-squared value is to 1, the better the model explains the variance in the target variable.
* Residual Analysis
> Residuals are computed (the difference between actual and predicted values), and their distribution is plotted to check for normality. Additionally, a scatter plot of residuals vs. predicted values is used to check for homoscedasticity (constant variance of residuals), which is important for validating the assumptions of linear regression.

<br>

## Technologies Used
- Python - version 3.x

## Libraries Used
- Pandas , Numpy , Matplotlib , Seaborn , sklearn

## Contributors
* [Ajay Markunda](https://github.com/ajay0304/)

# SURPRISE_HOUSING_ASSIGNMENT
Building Linear Regression using Ridge and Lasso Regularization Techniques for predicting the important features of House Price

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to 
predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.

__Business Goal__:
You are required to model the price of houses with the available independent variables.
This model will then be used by the management to understand how exactly the prices vary with the variables.
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

In this model we have used House price dataset


## Technologies Used
- Numpy -- version -1.24.3
- Pandas -- version -1.4.2
- Matplotlib -- version -3.5.1
- Seaborn -- version -0.11.2
- Scikit Learn -- version -1.0.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Conclusions
- dropping the variables which are with high number of missing values
- Removing the features which are highly correlated with each other which are observed in heatmap visualization
- Overall Quality, Ground Living Area & Garage Area variables are linear in relationship with the Sale Price which is observed in Pairplot visualization
- Obversed Skewness in the Distribution of Sale Price. So converted Sale Price using Logarithmic scale and uniform distribution is observed.
- After developing the models using Linear Regression, Ridge and Lasso Regression, from the results we concluded that Lasso Regression is better method to go. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Acknowledgements
- This project was given by UpGrad

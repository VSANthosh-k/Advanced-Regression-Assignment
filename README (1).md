# Project Name
>This assignment is a programming assignment wherein it is built a multiple linear regression model to detect the predictors of the Sales Price of the House.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. The company wants to know:

Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house. Also, determine the optimal value of lambda for ridge and lasso regression.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Hyperparameter Lambda:

Ridge : 5 -Lasso : 0.0001
Following factors are the good predictor and impact on the sales price of House and are possitively correlated:

Ridge : OverallCond, GrLivArea,  BsmtFullBath, LotFrontage	, Neighborhood_NridgHt.
Lasso : 'GrLivArea', 'OverallQual', 'Neighborhood_NoRidge', '2ndFlrSF' , 'LotArea'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Pandas - Version: 1.4.2
Numpy - Version: 1.21.5
seaborn - Version: 0.11.2
matplotlib - Version: 3.5.1
train_test_split from sklearn.model_selection
MinMaxScaler from sklearn.preprocessing
RFE from sklearn.feature_selection
LinearRegression from sklearn.linear_model
r2_score from sklearn.metrics

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
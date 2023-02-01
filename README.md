# house-pricing
house pricing assignment
Houses Prices Ridge Regression and Lasso Regression
<font color = blue >
    
## Introduction
</font>

### A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

### In such an attempt,Company want to know Which variables are significant for house pricingin.
>### How well those variables describe the house price
###  predict the actual value of the prospective properties
### whether to invest in them or not

## Table of Contents
* [General Info](#general-information)
* [Problem statement](#problem-statement)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
The Company want to know:
variables are significant for house pricingin.
>### How well those variables describe the house price
### predict the actual value of the prospective properties
### whether to invest in them or not
### determine the optimal value of lambda for ridge and lasso regression.

## Problem statement
</font>  

>####  The company wants to understand to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Best alpha value for Lasso : {'alpha': 0.001} Best alpha value for Ridge : {'alpha': 0.1}

After compairing both the models we can conclude that the following Features are vital to explore the DataSet MSSubClass RoofMatl_Membran MSZoning_RL MSZoning_FV MSZoning_RH MSZoning_RM Condition2_PosA RoofMatl_WdShngl

For Lasso regression, the R2 values for training and testing set are 0.9174442574972889, 0.855123192817482 and MSE values is 0.023838046736017564.
For Ridge regression, the R2 values for training and testing set are 0.9575101480652918, 0.7491779353883947 and MSE values is 0.018835107573615582. Results concludes that models are robust and generalized.

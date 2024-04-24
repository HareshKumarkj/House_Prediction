# Project Name

House Price Analysis

This project contains two section.
Part-I involves programming-modeling(to be submitted in a Jupyter Notebook), 
and Part-II includes subjective questions (to be submitted in a PDF file). 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularization in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

Downloads

Refer to the train.csv file.

## Conclusions

- The top 20 features impacting the price of the property are:

- Ridge model: Total_sqr_footage, GarageArea, TotRmsAbvGrd, OverallCond, LotArea, CentralAir_Y, LotFrontage, Total_porch_sf, Neighborhood_StoneBr, Alley_Pave, OpenPorchSF,
MSSubClass_70, RoofMatl_WdShngl, Neighborhood_Veenker, SaleType_Con, HouseStyle_2.5Unf, PavedDrive_P, KitchenQual_Ex, LandContour_HLS, SaleType_Oth.

- Lasso model: Total_sqr_footage, GarageArea, TotRmsAbvGrd, OverallCond, LotArea, CentralAir_Y, Total_porch_sf, Neighborhood_StoneBr, Alley_Pave, OpenPorchSF,             MSSubClass_70, LandContour_HLS, KitchenQual_Ex, BsmtQual_Ex, Condition1_Norm, Neighborhood_Veenker, MasVnrType_Stone, PavedDrive_P, LotFrontage, PavedDrive_Y

## Technologies Used

- libraries - numpy, pandas, matplotlib, seaborn, sklearn, statsmodel



# Modelling House Price using Regularization

**Problem Statement**

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and

- How well those variables describe the price of a house.

- Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goal**
We are required to model the price of houses with the available independent variables.
This model will then be used by the management to understand how exactly the prices vary with the variables.
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- Surprise Housing, a US-based company, is entering the Australian market. They aim to use data analytics to buy houses below market value and sell them at higher prices. The project involves building a regression model with regularization to predict house prices and identify key factors influencing these prices.

- Surprise Housing, has established a successful business model centered on data-driven property investments. By leveraging data analytics, the company identifies houses priced below their market value, purchases them, and sells them at a higher price for profit. Now, Surprise Housing plans to replicate this model in the Australian housing market. To ensure successful market entry and investment decisions, they require a robust regression model that can accurately predict house prices and highlight the significant variables influencing these prices.

- The project aims to solve the challenge of accurately predicting the market value of houses in the Australian market to aid Surprise Housing in making informed investment decisions. 

- The company has collected a data set from the sale of houses in Australia.

## Conclusions
- The median SalePrice is maximum for Floating Village Residential (FV) and mimimum for Commercial (C). Nonetheless, the saleprice distribution reaches the peak in case of Residential Low Density (RL).
- The median SalePrice is higher in case of paved street than in case of graveled street.
- The median SalePrice is maximum for HLS property-flatness-type at hillsides, wherein there is a significant slope from side to side and mimimum in case of Banked type (BNK) with abrupt significant rise from street grade to building.
- The median SalePrice changes only moderately with the lot configuration and the land slop.
- The median SalePrice is maximum for the Poured Contrete-type foundation and minimum for Slab type.
- The median SalePrice increases consistently with increasing exposure ('BsmtExposure') such as walkout or garden-level walls.
- The median SalePrice exhibits moderate changes with the rating of basement finished area (BsmtFinType1 and BsmtFinType2).
- The median SalePrice is maximum for gas-forced warm-air-furnace-type heating and minimum for gravity furnace.
- The median SalePrice is maximum for excellent heating quality ('HeatingQC') and condition and minimum for poor quality.
- The median SalePrice is higher in the presence of central air conditioning than without air conditioning.
- The median SalePrice is maximum for the electrical system equipped with standard Circuit Breakers & Romex and minimum for mixed-type electrical system.
- The median SalePrice does not fluctuate significantly with the home functionality ('Functional').
- The median SalePrice is maximum for the BuiltIn-type garage location ('GarageType') and minimum for Car Port-type garage location.
- The median SalePrice is maximum for finished interiors of garage ('GarageFinish') and minimum for unfinished.
- The median SalePrice is maximum for good garage quality ('GarageQual') and typical/average garage condition ('GarageCond') and minimum for poor garage quality and fair garage condition.
- The median SalePrice is maximum for paved driveway ('PavedDrive') and minimum for dirt/gravel paved driveway.
- The median SalePrice is maximum for partial-type sale condition ('SaleCondition') and minimum for adjoining-land-purchase-type sale condition.


## Technologies Used
- Python - 3.11.6
- Pandas - version 2.2.0
- Numpy - version 1.26.4
- Scikit-learn - version 1.4.1.post1
- Seaborn - version 0.13.2
- Matplotlib - version 3.8.3


## Acknowledgements
This Modelling House Price Project is a part of my assignment for Post Graduate Diploma Degree in AI & ML at IIIT-Bangalore

## Contact
Created by [@imkushwaha] - feel free to contact me!

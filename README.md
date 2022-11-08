# Advanced rgeressison using RFE, Lasso & Ridge
> Housing Price prediction using advanced regression Lasso & Ridge techniques


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

## Business Goal  

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
### Based on the features that rank topmost in multiple models, we can say the most important faetures cover:

- Features that related to useful area in the house:
`GrLivArea`: Above grade (ground) living area square feet
`1stFlrSF`: First Floor square feet
`2ndFlrSF`: Second floor square feet
`TotRmsAbvGrd`: Total rooms above grade (does not include bathrooms)

- Features that relate to Overall Quality in Material/Finish of the house:
`OverallQual`: Rates the overall material and finish of the house, especially:
     10    Very Excellent
     9    Excellent
     8    Very Good
`RoofMatl`: Roof material, especially
     WdShngl    Wood Shingles

- Feature for Garage space
`GarageCars`: Size of garage in car capacity

- Features about the Neighborhood, the more premium/tony/happening areas will have higher prices
`Neighborhood`: Physical locations within Ames city limits, especially
     NoRidge    Northridge
     NridgHt    Northridge Heights

- The feature for
`Kitchen`: Kitchens above grade/ground

- The no. of useful bathrooms above grade/ground
`FullBath`: Full bathrooms above grade

We saw that some of these were seen even during EDA to be important, either thru:
- Higher correlation for numeric features
- Box plots for Categoricals

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
numpy pandas matplotlib.pyplot seaborn statsmodels.api sklearn scipy
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- UpGrad Ml C42
- This project was based on [refer](https://learn.upgrad.com/course/3090/segment/23340/170871/522975/2684232).


## Contact
Created by [@ajayantrix] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
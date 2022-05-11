# House Pricing Prediction Assignment

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

## Table of Contents

- [House Pricing Prediction Assignment](#house-pricing-prediction-assignment)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Technologies Used](#technologies-used)
  - [Conclusions](#conclusions)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

## Technologies Used

1. numpy
2. pandas
3. matplotlib
4. seaborn
5. sklearn
   1) train, test
   2) MinMax Scaler
   3) Linear Regression
   4) RFE
6. statsmodel
7. variance inflation factor

## Conclusions

- Variables ***GrLivArea, OverallQual, LotArea, OverallCond, TotalBsmtSF*** are the most significant in predicting the price of house
- These variables explain 83% varaince in the model and as visible above can give decent accuracy on test set/ unseen data
  
## Acknowledgements

- This project is outcome of assignment on Advanced Linear Regression

## Contact

Created by [@jaskirat8] - feel free to contact me!

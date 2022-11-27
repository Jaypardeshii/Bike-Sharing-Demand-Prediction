# Bike-Sharing-Demand-Prediction
## Inrtoduction
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Problem statement
We are tasked with predicting the number of bikes rented each hour so as to make an approximate estimation of the number of bikes to be made available to the public given a particular hour of the day.

## Steps involved
Installing libraies and getting the dataset.
Performing EDA (exploratory data analysis).
Drawing conclusions from the data.
Preprocessing the data.
Training different models.
Evaluating metrics of all the models.

## Algorithms used
1. Linear regression
2. Lasso regression
3. Ridge regression
4. Elastic net
5. Polynomial
6. Decision tree
7. Random Forest
8. Gradient Boosting
9. XGBoost

## Conclusions
* The best accuracy algorithm for our test dataset is Xtreme Gradient boosting algorithm with Adj_R2 score of 0.928718. We have other algorithm such as polynomial, Gradient boosting, Random forest who also have optimal Adj_R2 score.
* The best accuracy algorithm for our train dataset is Decision tree algorithm with Adj_R2 score of 1. We have other algorithm such as Gradient boosting, Xtreme_GB and polynomial who also have optimal Adj_R2 score.
* Most important features for Gradient Boosting are temperature, humidity, functioning-day-Yes and functioning-day-No.
* Most important features for eXtreme Gradient boosting are functioning-day-No, season_winter and hour_18.

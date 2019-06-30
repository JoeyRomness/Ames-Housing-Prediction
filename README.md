# Ames Iowa House Price Prediction: Predicting Housing Prices with Linear Regression

## Problem Statement
Using the Ames Iowa Housing dataset, it is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

## Executive Summary
In order to get a working model that predicted housing prices in Ames, Iowa, This project will do the following:
> - 1: Clean the Train/Test datasets, filling in NaNs, changing and transforming datatypes/datatypes as needed.
> - 2: Conduct an EDA to determine what correlates with Saleprice and see other patterns between given data.
> - 3: Engineer new features for the dataset to increase model accuracy
> - 4: Build and fit a linear regression model that can predict housing prices.



### Conclusions
My final model had the following features as the most highly correlated with saleprice:
> - Quality-Interaction
> - Total SF 
> - Overall Qual
> - Ground Living Area
> - Exterior Quality
> - Kitchen Quality
> - Garage and Cars 
> - Total Bsmt SF
> - Garage Area
> - Ground Live Area and Total Rooms Aboveground Interaction
#### Afterthoughts
The one thing I'm worried about with all of this modelling I've been doing is that I may be overfitting my model. I scored high in the kaggle competition initially (3rd place) but I do worry that some of my engineered features are not very good.

###### ***Things I'd like to do in the future:*** 
> - Revisit feature engineering: make sure that none of the features I'm creating our harming my model's accuracy rather then improving it
> - On the other side of the coin -- because lasso regression removes insignificant features, what if I just made tons of features (ensuring that they were independent of one another). Could doing something like polynomial-features help our score?
> - I'd love to revisit this question using XGboost to see how accurate I can get my predictions with a different model.
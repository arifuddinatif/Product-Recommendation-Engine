


![App Screenshot](https://www.xenonstack.com/hubfs/xenonstack-deep-learning-based-recommendation-system.png)




## Inrtoduction
Amazon.com is one of the largest electronic commerce and cloud computing
companies.Amazon relies heavily on a recommendation engine that reviews
customer ratings and purchase history to recommend items and improve sales.we
are given a dataset which contains the customer reviews and ratings of beauty
related products sold on their website.


 


## Problem statement

We are tasked with building a recommender engine that reviews customer ratings
and purchase history to recommend items and improve sales.This engine looks at
the customers previous purchases and ratings and provides recommendations of
products similar to the products they like.




## Overview of the data
We are given the following columns in our data:
1. Unique userId - Unique id used for customer Identification.
2. Product ASIN  - Amazon's unique product identification code for each product.
3. Ratings - Ratings(1-5) given by customers based on their satisfaction.
4. Timestamp - Timestamp of the given rating in UNIX time.

## Steps involved
1. Installing libraies and getting the dataset.
2. Performing EDA (exploratory data analysis).
3. Drawing conclusions from the data.
4. Preprocessing the data.
5. Training the model.
6. Evaluating metrics of the model.

## Approaches used
1. Popularity based recommender system.
2. Collaborative filtering based recommender system.
- Knn
- Singular Value Decomposition

## Conclussion
Although using the popularity based model gave us an RMSE value of 1.3, with KNN we were able to get RMSE value of 1.05.Whereas using SVD got us an RMSE value of 1.01, but on further hyperparameter tuning it gave us an RMSE value of 0.87.

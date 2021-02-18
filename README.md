# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  Project 4: Recommendation System for Cocooncenter Pharmacy website


### Date
10 Feb 2021


## Overview
Forth project of the Data Science Immersive course with the General Assembly. It is building a Recommendation system for the Cocooncenter pharmacy dataset.

## Problem statement
In this project we will use the Cocooncenter pharmacy dataset is a recent collected data and avaliable in Kaggle. The aim is to build a recommendation system based on recorded information on the website. In this project, we will try to develop a set of algorithms to find the best recommended for the Cocooncenter Pharmacy by using Content-based Recommender which provides a recommending similar Items by selecting some of the features that will help to find a good result.

## Datasets

### Link to the Cocooncenter kernel in Kaggle:
https://www.kaggle.com/reemalsh/cocooncenter-care-products

### Data Dictionary

| Variable |	Description  |
|----------|-----------------|
| name | The name of product  |
|brand|The brand of the product|
|price_in_pound|The price in Pound £|
|stars|How many stars get the product |
|number of reviews|How many reviews get the product |
|url|URL of the product |
|description|Description of product |
|EAN_code| International Article Number like id|
|Form|The form of the product |
|size|The size of the product|
|availablty|is it in stock or not|


## Conclusions and Recommendations

In this project, we worked on the Cococenter pharmacy dataset, an interesting data hosted by Kaggle. In which, we tried to build a recommendation system by using given features that describe the products. 
To solve this problem, we used three features which are (Brand, Price, and number of reviews) to build this system, and we chose them to make good suggestions. In conclusion, we were able to build a recommendation system that can recommend similar products by using Content-Based. And we used a suitable algorithm that helped to get good results which are NearestNeighborsClassifier and KNeighborsClassifier with n=1 for both. In the end, the evaluation applied for those algorithms by using the LogisticRegression model and the accuracy for both algorithm above 90%.




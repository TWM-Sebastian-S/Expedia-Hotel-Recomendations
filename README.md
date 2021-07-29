# Expedia Hotel Recomendations

### This is one of my personal DS/ML/DL projects I've been working in since I started my career as a Data Scientist.

## Project Overview

Machine Learning Project in Python created to find out the key drivers that lead to churn and predict the customer churn.
Project included: 
  - Breakdown Problem Statement
  - EDA & database cleaning
  - Perform Univariate & bi-variate analysis for both numeric and categorical variables
  - Feature engineering and feature selection
  - Prepare the data for modelling
  - Create models using multiple algorithms with hyperparameter tuning
  - Compare the performance of different models using jaccard_score

## Problem Statement

**This is Kaggle competition that took place 5yrs ago. The following has been extracted from Kaggle.com.**

Planning your dream vacation, or even a weekend escape, can be an overwhelming affair. With hundreds, even thousands, of hotels to choose from at every destination, it's difficult to know which will suit your personal preferences. Should you go with an old standby with those pillow mints you like, or risk a new hotel with a trendy pool bar?

Expedia wants to take the proverbial rabbit hole out of hotel search by providing personalized hotel recommendations to their users. This is no small task for a site with hundreds of millions of visitors every month!

Currently, Expedia uses search parameters to adjust their hotel recommendations, but there aren't enough customer specific data to personalize them for each user. In this competition, Expedia is challenging Kagglers to contextualize customer data and predict the likelihood a user will stay at 100 different hotel groups.

The data in this competition is a random selection from Expedia and is not representative of the overall statistics.

## Code and resources used
**Python Version:** 3.7

**Packages:** Pandas / Numpy / Seaborn / Scikitlearn

**ML Resources:** Logistic Regression / Gradient Boosting / Cross-validation / AUC / ROC / Confusion Matrix

## Model Building

Given that all models tried were performing quite low, I tried several algorithms.

- Random Forests
- Naive Bayes
- Logistic Regression
- KNN
- XGBoost
- Decission Tree

## Model Performance

The Jaccard similarity index (sometimes called the Jaccard similarity coefficient) compares members for two sets to see which members are shared and which are distinct. It’s a measure of similarity for the two sets of data, with a range from 0% to 100%. The higher the percentage, the more similar the two populations. Although it’s easy to interpret, it is extremely sensitive to small samples sizes and may give erroneous results, especially with very small samples or data sets with missing observations.

![Model Performance Comparison](https://github.com/TWM-Sebastian-S/Expedia-Hotel-Recomendations/blob/main/Model%20Performance%20Comparison.JPG "Model Performance Comparison")



## Conclusion

I created a function to calculate the probability to include in a basket of 5 options and that increased significantly the percentage of accuracy.




[GitHub Repository](https://github.com/TWM-Sebastian-S/Expedia-Hotel-Recomendations)

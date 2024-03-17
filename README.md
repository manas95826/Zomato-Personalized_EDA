# Zomato Dataset Exploratory Data Analysis and Machine Learning Modeling

Welcome to the Zomato Dataset Exploratory Data Analysis and Machine Learning Modeling project! This project aims to provide insights into Zomato's restaurant data and develop machine learning models to predict customer satisfaction.

## Introduction

**Dataset Description:**  
The dataset consists of various attributes related to restaurants listed on Zomato, including information such as restaurant name, location, online ordering, ratings, cuisines, and more.

## Table of Contents

1. **Introduction**: Brief overview of the project and dataset.
2. **Exploratory Data Analysis**: Analyzing the dataset to answer specific questions and gain insights.
3. **Data Wrangling**: Preprocessing the data by handling missing values, encoding categorical variables, and preparing it for modeling.
4. **Feature Engineering**: Transforming and creating new features to improve model performance.
5. **Machine Learning Models**: Building machine learning models to predict customer satisfaction.
6. **Hyperparameter Tuning**: Optimizing model parameters for better performance.
7. **Summary and Interpretation**: Summarizing key findings and providing insights.

## Exploratory Data Analysis

1. **Percentage of restaurants accepting online orders**: 59% of restaurants support online orders.
2. **City with higher average ratings**: Church Street has the highest average ratings, while Electronic City has the lowest.
3. **Most common restaurant type and its rating**: Quick Bites is the most common restaurant type, and restaurants providing delivery services tend to have higher ratings.
4. **Relationship between price and rating**: Contrary to expectations, expensive restaurants tend to have higher ratings.
5. **Linear correlation analysis**: Moderate correlation between rating and votes, weak correlation between price and rating.
6. **Purchasing power in Bangalore**: Church Street has the highest purchasing power, while Banashankari has the lowest.
7. **Effect of book table reservation and online order on ratings**: Restaurants offering table reservation tend to have higher ratings.

## Data Wrangling

1. **Handling missing values**: Imputed missing values in 'rate' and 'approx_cost(for two people)' columns.
2. **Feature selection**: Dropped irrelevant columns like 'url', 'address', 'phone', etc.
3. **One-hot encoding**: Converted binary categorical columns ('online_order', 'book_table') to numeric values.
4. **Standardizing format**: Converted multivalued columns ('dish_liked', 'cuisines') to 1st normal form.

## Machine Learning Models

1. **Logistic Regression**: Achieved an accuracy of 80%.
2. **Random Forest**: Achieved an accuracy of 85%.
3. **XGBoost**: Achieved an accuracy of 88%.

## Hyperparameter Tuning

Performed grid search cross-validation to find optimal parameters for Random Forest model.

## Summary and Interpretation

- Church Street emerges as a hotspot with both higher purchasing power and ratings.
- Book table reservation significantly impacts restaurant ratings.
- No direct linear correlation found between numerical features.
- High-class expensive restaurants tend to have better ratings.
- Quick Bites restaurants are the most common.

## Conclusion

This project provides valuable insights into Zomato's dataset and offers predictive models to understand customer satisfaction better. By leveraging machine learning techniques, Zomato can enhance its services and improve customer experiences.

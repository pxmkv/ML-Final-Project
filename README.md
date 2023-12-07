# Movie Gross Prediction

## Overview

This repository contains the code and data for a machine learning project focused on predicting the gross earnings of movies based on various features such as rating, genre, score, votes, budget, production company, runtime, Consumer Price Index (CPI), month, and day of the week. The project employs analytical methods like random forest, regression, and recurrent neural networks (RNN) to make informed predictions based on historical data.

## Motivation

The goal of this project is to predict the box office gross of movies using a set of relevant features. Accurate predictions can be valuable for movie studios, actors, and other stakeholders in the film industry to make informed decisions about movie releases and investments.

## Data

The data is sourced from a dataset that includes movie information, such as rating, genre, score, votes, budget, production company, runtime, CPI, month, and day of the week. This dataset provides a comprehensive set of features that can be used to predict movie gross.

A potential challenge with this data is ensuring data quality, as there may be missing or incomplete information about certain movies, genres, or other features. This challenge is addressed through data cleaning and imputation techniques.

## Analytic Methods

A variety of analytical methods are utilized, including:

1. **Random Forest**: Random Forest is suitable for this dataset as it can handle both continuous and categorical variables. It helps capture complex relationships between the provided features and movie gross.

2. **Regression**: Regression analysis quantifies the impact of each feature on movie gross. It provides insights into which factors are most influential in determining box office earnings.

3. **Recurrent Neural Networks (RNN)**: RNNs are employed for sequential data like time series. In this case, RNNs can capture temporal dependencies in the data, potentially improving the accuracy of gross predictions.

## Risks

There is a risk of over-reliance on the predictions without considering the model's limitations, which could lead to suboptimal decisions in the film industry.

Cultural and regional factors may affect the model's performance, and using a generalized model may not account for all nuances, potentially leading to inaccurate predictions.



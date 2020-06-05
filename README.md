# Airbnb Listings - Will a listing have a high booking rate or not?

The question in the title pretty much sums up the modeling problem we aim to solve - classification of Airbnb listings into those which are highly likely to have high booking rates and those which don't.

In this project *given by my professor who took the course 'Data Mining and Predictive Analytics', we use the data of 100,000 labelled samples to train a variety of models and how they perform on a test set of 12K samples. 

Each listing was described by 70 features (numerical - price, beds; text - house_rules, amenities; categorical - property_type, host_is_superhost; and a couple of date columns). 

This data got me ample opportunity to flex my cleaning and feature engineering brain muscles. 

## Libraries 

- caret, dplyr, tidyr, tidyverse, lubridate, rapportools, qdap were used for cleaning and feature engineering
- ggplot2, ggthemes for EDA
- e1071, randomForest, xgboost for modeling

## Model Evaluation

The aim is to find the model which can yield the best prediction accuracy. Hence, the most important metric for evaluating each model was accuracy. 

### Baseline

We used the majority class classifier as our baseline model (with the majority class being 0) which gave an accuracy of 75.532%. At the very basic level, whatever model we built had to beat this baseline. 


## ML Models

- Logistic Regression
- Naive Bayes
- Random Forest
- XGBoost

_________________________________________

I have included the executive summary for this project in this repo. It has a pretty detailed overview of the approach I took from start to finish. 
This was a really fun project especially with regard to feature engineering.

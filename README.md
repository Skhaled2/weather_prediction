# weather_prediction
This repository contains a project for weather prediction using data analysis, feature engineering, and machine learning. The goal is to predict weather conditions based on historical data, applying regression techniques and converting the results into a classification task.

Project Overview

Data Analysis:

Initial exploration and analysis of the dataset to understand the distributions, correlations, and significance of different features such as temperature, humidity, wind speed, visibility, pressure, etc.

Feature Engineering:

Creation of new features to improve the predictive power of the model. This may include handling missing values, encoding categorical variables, scaling numerical features, and deriving additional features from the existing ones.

Model Building:

A regression model was initially applied to predict continuous weather-related outcomes.

The regression output was converted into a classification task by applying a threshold to determine different weather categories (e.g., sunny, cloudy, rainy).

Classification:

The classification was refined based on the results from the regression model. Several metrics like accuracy, precision, recall, and F1-score were used to evaluate the performance.

Results

The model achieved satisfactory performance with the following metrics:

Accuracy: 99%
Precision: 100%
Recall: 99%
F1-Score: 99%

Requirements

Python 3.x
Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, etc.

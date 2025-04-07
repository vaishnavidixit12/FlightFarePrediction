# Flight Fare Prediction

This repository contains a Jupyter Notebook for predicting flight fares using machine learning techniques. The original code is based on the Kaggle notebook by [Vaishnavi Dixit](https://www.kaggle.com/code/vaishnavidixit12/flight-fare-prediction), adapted for local use and further experimentation.

## Project Overview

The objective of this project is to build a regression model that predicts airline ticket prices based on several features such as:
- Airline
- Date of Journey
- Source and Destination
- Route
- Duration
- Number of Stops
- Additional Info

## Dataset

The dataset used in this project is publicly available on Kaggle under the title **Flight Fare Prediction**. You can find it [here](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh).

## Features Engineering

The notebook includes extensive feature extraction and transformation:
- Extraction of day, month, hour, and minutes from timestamp fields
- Conversion of categorical variables using `LabelEncoder` and `OneHotEncoder`
- Imputation of missing values and format normalization

## Model Building

The following models are evaluated:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor (with hyperparameter tuning using `GridSearchCV`)
- XGBoost Regressor

Evaluation metrics include:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Results

The **Random Forest Regressor** and **XGBoost Regressor** performed the best, achieving strong predictive accuracy. Hyperparameter tuning further improved performance.

## Repository Structure

```
.
├── flight_fare_prediction.ipynb    # Main notebook with code and analysis
└── README.md                       # This readme file
```



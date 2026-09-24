# Uber Data Analysis & Pickup Demand Prediction

An end-to-end Uber analytics and machine learning project focused on understanding pickup demand patterns and predicting hourly Uber pickups using Random Forest Regression.

## Project Overview

This project analyzes Uber pickup demand using historical data containing:

- Pickup timestamps
- Borough/location
- Number of pickups
- Traffic speed
- Visibility
- Temperature
- Dew point
- Atmospheric pressure
- Precipitation
- Snow depth
- Holiday information

The project combines **Exploratory Data Analysis (EDA)** with **Machine Learning** to derive business insights and predict Uber pickup demand.

## Objectives

- Analyze Uber pickup demand patterns over time and location.
- Identify important factors affecting pickup demand.
- Study the relationship between weather, traffic, time, and Uber pickups.
- Build a Random Forest Regression model to predict hourly pickup demand.
- Evaluate model performance using MAE, RMSE, and R².

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

## Machine Learning

### Problem Statement

Predict the number of Uber pickups for a given hour using historical temporal, location, traffic, and weather-related information.

### Target Variable

`pickups`

### Features

The model uses:

- Borough
- Traffic speed
- Visibility
- Temperature
- Dew point
- Atmospheric pressure
- Precipitation
- Snow depth
- Holiday indicator
- Hour
- Day
- Month
- Day of week
- Weekend indicator

### Model

**Random Forest Regressor**

```text
n_estimators = 100
random_state = 42

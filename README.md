# NYC Taxi Trip Duration Prediction (Deep Learning)

This project applies deep learning regression models to predict NYC taxi trip duration using historical taxi trip data and weather features.

## Problem
Accurate trip duration prediction helps improve transportation planning, pricing, and operational efficiency in urban environments.

## Data Sources
- NYC Yellow Taxi Trip Data (January 2020)
- Meteostat Weather Data (Wall Street, NYC)

## Feature Engineering
- Removed outliers (trip duration ≤ 0 or > 180 minutes)
- Extracted temporal features (hour, day of week)
- Integrated weather features (temperature, precipitation, wind speed)
- Applied log transformation and feature standardization

## Models
- Linear Regression (baseline)
- MLP
- Deep Neural Network (TensorFlow)
- Deep Neural Network (PyTorch)

## Results
- Best model: DNN with Adam optimizer
- Validation MAE ≈ 0.224
- Comparable results across TensorFlow and PyTorch

## Technologies
Python, TensorFlow, PyTorch, Scikit-learn, Pandas, NumPy, Matplotlib

## Files
- `notebooks/NYC_Taxi_Deep_Learning.ipynb`
- `report/Deep_Learning_for_NYC_Taxi_Trip_Duration_Prediction.pdf`

# NYC Taxi Trip Duration Forecasting with Stacked Regression

This project predicts NYC taxi trip durations using stacked ensemble regression models. It includes end-to-end steps from data cleaning, outlier treatment, distance calculation, feature engineering, model selection, cross-validation, and performance evaluation.

---

## Features
- Reads and processes NYC taxi dataset (nyc_taxi_trip_duration.csv)
- Calculates distance using geopy (geodesic) from coordinates
- Outlier detection and removal for both trip duration and distance
- One-hot encoding and correlation analysis
- Trains multiple regression models:
  - K-Nearest Neighbors (KNR)
  - Stochastic Gradient Descent (SGDR)
  - Gradient Boosting Regressor (GBR)
  - Bayesian Ridge (BR)
  - Linear Regression (LR)
- Hyperparameter tuning with GridSearchCV
- Stacked regressors with varying final estimators (KNR, GBR, LR)
- Performance metrics:
  - R² Score
  - Mean Absolute Error (MAE)
  - Computation Time

---

## Visualizations
- Box plots for outlier detection
- Scatter plots of Distance vs Trip Duration
- Heatmap of feature correlations

---

## How to Run
1. Upload nyc_taxi_trip_duration.csv via Google Colab or local Jupyter
2. Run the notebook from top to bottom
3. The models train and output results automatically

---

## Requirements
See [requirements.txt](requirements.txt)

---

## Author
*Akhdan Arifuddin*

# air-quality-predictions-ml
Time-series machine learning model for predicting urban air quality (UCI dataset)

# Air Quality Prediction Using Machine Learning

## Overview
This project builds a time-series forecasting model to predict harmful urban air pollutant levels using data from the UCI Machine Learning Repository. The goal is to enable proactive health alerts and support smarter city planning.

## Techniques
- Data cleaning (interpolation, outlier filtering, normalization)
- Feature engineering (rush-hour, seasonal patterns)
- Models: Linear Regression, Random Forest, Gradient Boosting
- Evaluation: RMSE, MAE, R² (time-series cross-validation)

## Results
- Random Forest achieved 15–31% lower error compared to baseline.
- Improved early-warning lead time by **3×** over naive methods.

## How to Run
1. Clone this repo
2. Open `Air_Quality_Prediction.ipynb` in Google Colab
3. Install requirements: `pip install -r requirements.txt`
4. Run all cells

## Dataset
[UCI Air Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Air+Quality)

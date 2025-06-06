# Woxsen Temperature Forecasting Using ML & Time Series Models

This project focuses on **accurate temperature prediction** using high-frequency weather station data collected every 15 minutes for six months at our university campus. By combining traditional time series methods and state-of-the-art deep learning models, we demonstrate how machine learning can significantly improve short-term weather forecasting accuracy.

## Project Overview

Accurate weather forecasts are essential across sectors like:
-  Agriculture
-  Disaster Management
-  Transportation
-  Energy Planning

This study implements multiple models to predict temperature values with high precision and reliability, enabling better risk mitigation and planning.

## Models Implemented

- **Auto ARIMA**: Dynamic parameter tuning for time series stationarity.
- **LSTM & Bi-LSTM**: Deep learning models to capture sequential patterns.
- **GRU**: A lighter, faster RNN variant optimized via hyperparameter tuning.
- **Random Forest**: Ensemble model for boosting performance through tree averaging.

##  Evaluation Metrics
-  **Mean Absolute Error (MAE)**
-  **Root Mean Squared Error (RMSE)**
-  **Mean Absolute Percentage Error (MAPE)**
-  **R² Score**

## Preprocessing Steps
- Handling missing values
- Outlier detection
- Feature engineering (rolling statistics, lag features)
- Normalization & scaling
- Train-test splitting

## Results & Insights
Comparative analysis shows that deep learning models like **LSTM** and **GRU** outperform traditional statistical models in capturing complex temporal dynamics. However, **Auto ARIMA** offers interpretability and ease for univariate series. These findings underscore the potential of AI-driven methods in meteorology.

## Dataset

> **Note:** The original dataset is private due to institutional confidentiality. 


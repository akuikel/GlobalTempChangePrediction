# Global Temperature Change Prediction

**Predicting the next 10 years of global temperature change using LSTM (3 layers) model based on 116 years of data.**

## Description

Global climate change is an ongoing issue with observable effects. Using temperature data from 1880 to 2020, we built an LSTM model to predict the global temperature for the next 10 years. By training the model on historical temperature anomalies, our goal is to help forecast the future temperature trends and provide insights on potential climate impacts.

## Approach

- **Dataset**: 116 years of global temperature anomalies (1880-2020).
- **Model**: LSTM (3 layers) for time series forecasting.
- **Data Prep**: Cleaned data with annual average temperature for each year.
- **Training/Testing**: 90% training, 10% testing for prediction.
- **Output**: Predicts the temperature anomalies for the next decade.

## Key Metrics

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R-squared (R²)**

These metrics were calculated for model evaluation.

## Future Scope

- Incorporating real-time data for ongoing predictions.
- Expanding to include other climate factors like rainfall, sea levels, and natural disasters.
- Extending the project to include social sustainability models and environmental impact analysis.


# energy-forecast-midwest
Forecasting Demand of Energy in the Midwestern Region of the United States

This project explores time series forecasting within the energy sector, with a specific focus on electricity demand forecasting. The time-series data for energy consumption has been obtained from the EIA government website. After the preliminary analysis, the data was found to have seasonality. For training and evaluating the model performance, data was split into training and testing subsets using an 80-20 split ratio. The energy consumption values were forecasted using SARIMA and LSTM. The classical SARIMA model outperformed the LSTM model with the RMSE values for the two models being 7.72 and 16.34 respectively.

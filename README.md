Stock Price Analysis with Machine Learning Models

This repository contains a Jupyter notebook that performs stock price analysis and prediction using machine learning models. The project primarily focuses on comparing historical stock prices and using LSTM (Long Short-Term Memory) networks for future price prediction.

Features

Stock Price Plotting: Visualizes the highest stock prices of multiple companies.
Machine Learning Models: Implements LSTM networks for time series prediction of stock prices.
Preprocessing: Includes features like moving averages and RSI (Relative Strength Index) for enhanced predictions.
Cross-Validation: Uses k-fold cross-validation to validate the model's performance.
Models Used

LSTM (Long Short-Term Memory): A type of recurrent neural network (RNN) designed to work with time series data for predicting future stock prices.
Evaluation Metrics:
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R² Score (Coefficient of Determination)
Requirements

Data

You can either provide pre-downloaded stock data or fetch real-time data using yfinance. The notebook also includes preprocessing steps like calculating Moving Averages and RSI.

Example

The notebook provides an LSTM model that predicts future stock prices based on historical data:

Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

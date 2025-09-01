# TATA Stock Price Prediction Using LSTM

Overview:
This project uses a Long Short-Term Memory (LSTM) deep learning model to predict TATA stock prices using historical NSE data. The workflow includes data preprocessing, sequence generation, model training, prediction, visualization, and estimation of potential profit or loss.

Features:
The model preprocesses the historical stock data using normalization, generates 60-day sequences to predict the next day’s price, and uses a multi-layer LSTM with Dropout to prevent overfitting. It predicts stock prices, visualizes actual versus predicted prices using Matplotlib, and estimates expected profit or loss.

Dataset:
The dataset contains historical TATA stock data in CSV format with columns such as Date, Open, High, Low, Close, and Volume. The 'Open' price is used as input for prediction.

Requirements:
Python 3.x, numpy, pandas, tensorflow / keras, scikit-learn, matplotlib.

Results:
The project generates a plot comparing actual vs predicted stock prices and calculates the approximate profit or loss based on predictions.

Future Work:
Potential improvements include hyperparameter tuning for higher accuracy, adding more features like Volume, High, and Low prices, and experimenting with other models such as GRU or ARIMA.


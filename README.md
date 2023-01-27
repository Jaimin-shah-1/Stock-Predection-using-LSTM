# Stock-Predection-using-LSTM
Stock Price prediction using-Long Shot Term Memory 
This project aims to predict the future stock prices of a company using historical stock data. The prediction is based on machine learning techniques, specifically using a Long Short-Term Memory (LSTM) neural network. The LSTM algorithm is used as it is well-suited for time series data, which is what stock prices are. The LSTM network will be trained on the historical stock data using a training set, and then tested on a separate test set to evaluate its performance.

Data - 
The data used for this project is historical stock prices for a specific company. The data includes the date, open, high, low, close, and volume of the stock. This data is obtained from a financial API such as Yahoo Finance. The data is then preprocessed, which includes cleaning and normalizing the data, as well as splitting it into a training and test set.

Requirements - 
To run this project, you will need to have Python and the following libraries installed:

TensorFlow
Keras
Pandas
Numpy
yfinance 
matplotlib
seaborn
scikitlearn

Input the Stock Ticker name of the company for which you want to predict the stock prices
Input the date range for which you want to predict the stock prices
Results - 
The results of the prediction will be plotted and a comparison between the predicted and actual stock prices will be shown. The model will also be used to make predictions for the next n days.

Note - 
It's important to note that stock market is very dynamic and hard to predict and this project is for educational and research purpose only. It's not recommend to use this model to make investment decisions. It's always good to consult with financial advisor before making any investment decisions. Also, the performance of the model can be improved with more data and fine tuning of the hyperparameters of the model.

Overview:

This project involves the analysis and prediction of the USD to Euro currency exchange rate using data scraped from Yahoo Finance. The primary goal is to forecast future exchange rates using time series modeling techniques, specifically the ARIMA and LSTM models.

Data Collection:

Data was scraped from Yahoo Finance using the yfinance Python library. The dataset includes historical USD to Euro exchange rates.

Data Preprocessing:

Handling missing values

Converting date columns to datetime format


Modeling:

ARIMA
The ARIMA (AutoRegressive Integrated Moving Average) model is a popular statistical method for time series forecasting. It combines three components: AutoRegression (AR), Integration (I), and Moving Average (MA).

LSTM
The LSTM (Long Short-Term Memory) network is a type of recurrent neural network (RNN) that is well-suited for sequential data and time series forecasting. It can capture long-term dependencies and patterns in the data.

Results:

The results of the models, including evaluation metrics and visualizations of the predicted vs actual exchange rates, are presented in the respective Jupyter notebooks.

Usage:

To reproduce the results or use the models, follow these steps:

Clone the repository:

git clone https://github.com/yourusername/time-series-Euro-USD.git

cd time-series-Euro-USD


Contributing:

Contributions are welcome! Please fork the repository and submit a pull request.

License:

This project is licensed under the MIT License. See the LICENSE file for details.


# Time-Series Analysis of VTSAX

This is a project for time-series analysis of the adjusted closing price of VTSAX shares. 

In this project, I first built a web scraper to collect data from Yahoo Finance website. Then, I conducted time series decomposition to analyze the data, to gain an understanding of which type of models will be best suited for the data.

I constructed a seasonal ARIMA model that outperformed naive forecasting methods, evaluated using mean absolute percentage error. 

As a bonus learning exercise, I constructed a LSTM model to compare the classical vs the modern methods of forecasting. It turned out that the small dataset size favored the classical model greatly, which signifies the time-tested robustness of traditional forecasting approaches.

As a disclaimer, please do not modify your investment strategies according to the models created through this project. The dataset's feature space does not have the explanatory power required for reliable prediction the target variable. Profitable forecasting of stock prices is not possible with limited data. 

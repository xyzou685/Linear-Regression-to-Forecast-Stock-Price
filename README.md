# Log_linear-Prediction-of-VOO-Price
Used linear regression to forecast and visualize the VOO Stock price and its confidence band in order to provide reference when trading. It is applicable to any stock data from Yahoo Finance (https://finance.yahoo.com/), but be aware that generally only the ETFs have their R^2 higher than 0.9. Also, this method only works for long-term trading.

Statistical Model : log(Daily VOO Close Price)~Days(i.e. row number of the dataset, the first row is considered as day 1, etc.)

# Google Stock Price Predictor Time Series Analysis (Python)

## Background
It has been said that the stock market is impossible to predict.  If it were possible, we would all do just that and become very wealthy.  To this I say if you don't believe impossible can happen, then you are right.  Now it may not be difficult to predict prices with 100% accuracy, but what if we could create a model accurate enough to make useful predictions on a stock given its histoical patterns and behaviors?  This will be the challenge to tackle in this project. 

## Business Problem
Even the most profitable investment firms struggle at times to predict future stock prices.  This can be due to a number of factors such as market shifts, economy swoons and swells, or international events which can all lead to unexpected influcences in the perforance of a stock.  With that said, lets see how well we can predict the future of Google's daily closing stock prices.

## Client
Prospective and current google stockholders.

## Objective 
Pull in historical stock data for Google and create a time series model which predicts the daily closing stock price for this stock with as greatest accuracy as possible for the purposes of making future investment decisions for our stockholders as well as creating marketing material to showcase why prospective cliens would want to invest their money with our firm.

## Solution

I created a time series model using ARIMA modeling coupled with grid search to find the optimal parametes to use given the behavioral patterns and trend the data displayed. 

## Result
The model was able to predict 2017 Google stock prices with a 102.98 root mean square error.  The range of the close price goes from under 200 to over 1200.  Considering this range, an RMSE of 102 with a range of data over 1000 is a good estimator. 

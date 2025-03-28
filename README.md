# stock_price_predictor
I aimed to predict stock prices and develop a strategy (Hold, Buy, or Sell) based on historical data. I used the following techniques and models:

Stock Price Prediction - 'Close' Column

Linear Regression: I used linear regression as my final model for predicting the 'Close' price of stocks. Although I experimented with ARIMA initially, it didn't perform as well as linear regression. You can find the ARIMA code in the repository as well.
Strategy Prediction

Ensemble Learning: To predict the 'Strategy' (Hold, Buy, or Sell), I leveraged ensemble learning techniques.
XGBoost: I employed the XGBoost model as one of the ensemble base models.
Soft Voting: The final prediction for the strategy was made using soft voting among the ensemble models.

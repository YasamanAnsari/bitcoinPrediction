# bitcoinPrediction
I have collected data about Bitcoin in a 5-year period and the features are open,price,high,low and volume which indicate respectively The open positions(either buy or sell ), bitcoin’s price , maximum and minimum prices, number of shares  bought and sold .
Since I was concerned about over-fitting , I used regularization methods like Ridge and Lasso regression
after some data cleansing, I used ElasticNet from sklearn which is Linear regression with combined L1 and L2 priors as regularizer.

Next steps:
• Using XGBoost and CatBoost algorithms
• Using gold data to indicate if it has correlation with BTC
• Using some important indicators for more precise predict of BTC price
• Predict btc price real-time and  for smaller time frames

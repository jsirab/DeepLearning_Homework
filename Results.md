# DeepLearning_Homework
## LSTM Stock Predictor

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency.

For this test we run for windows from 1 to 10 and we used an Epoch = 20




### Learning Loss

-------------------------------------------
| window size | FnG Index | Closing price |
| :---------: | :-------: | :-----------: |
|1|0.0960|0.0244|
|2|0.1014|0.0299|
|3|0.1088|0.0263|
|4|0.1156|0.0295|
|5|0.1131|0.0284|
|6|0.1101|0.0296|
|7|0.1175|0.0279|
|8|0.1185|0.0296|
|9|0.1037|0.0248|
|10|0.1154|0.0249|

-------------------------------------------














* Which model has a lower loss?

The closing Price model has a Lower Loss

* Which model tracks the actual values better over time?

The Closing price model follows much closer the actual price

* Which window size works best for the model?

Window= 1 for Both Fear & Greed Model and Closing price model
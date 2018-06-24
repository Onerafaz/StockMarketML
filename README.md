# StockMarketML

Using the magic of machine learning to predict the trends of the stock market.

### Tools/libs Used
* [Keras](https://keras.io/)
* [Numpy](http://www.numpy.org/)
* [Praw](https://praw.readthedocs.io/en/latest/)
* [Requests](http://docs.python-requests.org/en/master/)

## App

Applying the Model

![app screenshot](https://user-images.githubusercontent.com/6625384/40280636-7ac6908a-5c1c-11e8-9d96-ededc88cb233.png)

## Lab 3

##### CollectData

This script gathers headlines/media data from various sources.

##### MultiHeadlineTickForcasting

Creates and trains a model to predict stock prices based on multiple headlines and historical tick data.

![lab 3 model](https://raw.githubusercontent.com/sshh12/StockMarketML/master/lab3/model.png)

## Lab 2

2nd Attempt

##### CollectData

This script gathers headlines/media data from various sources.

##### HeadlineAnalysisAndPrediction

Creates and trains a model to predict stock prices based on headlines.

##### HeadlineTickAnalysisAndPrediction

Creates and trains a model to predict stock prices based on headlines and historical data.

##### HeadlineTickAnalysisAndPrediction2

Creates and trains a model to predict stock prices based on headlines and historical data with a slightly different configuration.

##### MultiHeadlineAndTickPrediction

Creates and trains a model to predict stock prices based on multiple headlines and historical data.

## Lab 1

1st Attempt

##### CollectData

This script gathers data by scraping websites and does basic word processing.

##### LoadData

This helper script loads the csv files and preprocesses data before being used in a model.

##### BasicPredictionClassification

This uses a window of the last n stock closes and volumes to predict whether the next close with be high or lower than it opened.

##### BasicPredictionRegression

This uses a window of the last n stock prices to predict the next close price.

##### HeadlinePredictionClassification

This uses headlines processed through doc2vec to predict changes in close price.

##### HeadlineAndTickerClassification

Using historic stock prices and headlines to predict close price.
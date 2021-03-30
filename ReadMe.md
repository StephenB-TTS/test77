# Bot-Time
![](images/bot-time.jpg)

# Project 2 Fintech 
- The Bot-Time project resulted in the building of a profitable automated trading bot that uses deep learning to make trades on Webull.
- A demo account has been setup on WeBull that is being migrated to a live trading account.
- Several RNN were constructed and fit to determine buying and selling decisions.
- We will compare the performance of these models and potentially combine their choices to build an automated trading bot.
- Dash Gallery was used to create the front-end that enables user to monitor the bots performance and adjust the dominant model taking trades.

# The Project
## Gathering the Data:
This is how we read-in the data:
![](images/get_data.PNG)
![](images/load_data.PNG)

## Test-Train-Split:
Preparing the data for the model.
![](images/test_train_split1.PNG)
![](images/test_train_split2.PNG)

We trained the data.
![](images/train1.PNG)
![](images/train2.PNG)

## Load for Dash:
Data is being prepared so it can be displayed in Dash.
![](images/load_for_dash.PNG)

## Get Final Data:
This function takes the "model" and "data" dict to construct a final dataframe that includes the features along with true and predicted prices of the testing dataset
![](images/get_final_data1.PNG)
![](images/get_final_data2.PNG)

## Prediction:
![](images/predict_function.PNG)

## Accuracy:
![](images/calc_accuracy.PNG)

# Data Visualizations:
When deciding on a trading strategy, one might consider using indicators to help guide the decision whether to buy, sell or hold a position. Some of the indicators explored in the Bot-Time project are Bollinger Bands, EMA Crossover Point and RSI Indicators.  Here are some illustrations that show how they were used in the Bot-Time strategy.

## Plot:
![](images/prediction_plot.PNG)

## Some Dash Visualizations:
Bollinger Bands:
![](images/Bollinger_Bands.png)

![](images/Candlestick.png)

EMA Crossover Points:
![](images/Crossover.png)

Prediction Chart:
![](images/Prediction.png)

RSI Indicator Chart:
![](images/RSI.png)

Webull Options Chain:
![](images/Webull_Options_Chain.png)

## Final Analysis:
Throughout the project, several models were tested, however, our third model proved to be the most accurate.




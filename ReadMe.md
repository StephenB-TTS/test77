# Bot-Time
![](images/bot-time.png)

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

## Reading In The Data:
This is how we read-in the data:
1. Stock Tickers Price Data
![](images/load_data.PNG)

## Test-Train-Split:
We had to drop columns, set/reset indexes, replace values. We also had to use try & except statements to read in the data without ending the functions on error.
![](images/test_train_split.PNG)

![](images/train1.PNG)
![](images/train2.PNG)

## Load for Dash:
- This is the 1st combined dataframe of the stock price & summary info:
![](images/load_for_dash.PNG)


This function takes the "model" and "data" dict to construct a final dataframe that includes the features along with true and predicted prices of the testing dataset
![](images/get_final_data1.PNG)
![](images/get_final_data2.PNG)

## Prediction:
![](images/predict_function.PNG)

## Accuracy:
![](images/calc_accuracy.PNG)

#Data Visualizations:
## Plot:
![](images/prediction_plot.PNG)

## Some Dash Visualizations:
Bollinger Bands:
![](images/Bollinger_Bands.png)

Interactive Candlestick Chart with panel selector:
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


When deciding on a trading strategy, one might consider using indicators to help guide the decision whether to buy, sell or hold a position. Some of the indicators explored in the Bot-Time project are Bollinger Bands, EMA Crossover Point and RSI Indicators.  Here are some illustrations that show how they were used in the Bot-Time strategy


===============================================================================
## Charts & Analysis:
### (Sum Total column indicates the ranking values)
1. These are the Communications & Consumer Sector Rankings:
![](images/add_image.png)
2. These are the Energy & Financial Sector Rankings:
![](images/add_image.png)
3. These are the Tech Sector Rankings:
![](images/add_image.png)
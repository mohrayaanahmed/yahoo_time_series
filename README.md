# yahoo_time_series
Segmentation, linear regression and next-day forecasting on four different time-series stocks.

Four stocks' data of the past three years (2018-2021) was downloaded from the yahoo finance website. SOURCE = https://uk.finance.yahoo.com/
The stocks that were worked on were:
1. RMG - Royal Mail PLC
2. NWG - Natwest Group PLC
3. JET - Just Eat Takeaway
4. AHT - Ashford Hospitality Trust

The missing values were first ascertained as to why they were missing. Then, linear regression was used to model and predict future closing price of all four stocks. Segmentation analysis was used to segment each time-series on different time parameters at t = 0.1, 0.2, and 0.4. Then, next-day forecasting was used to forecast the next day closing price of a stock by predicting it as its previous day closing price. Next-day forecast was then plotted along with its residuals.

Various descriptive statistics were performed on these four time-series and their results are plotted in each py file. 

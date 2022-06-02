# yahoo_time_series

# Data Analysis on four Yahoo Time-series stocks

### **Project Objective:**
Four stocks' data of the past three years (2018-2021) was downloaded from the yahoo finance website. The time-series data was then subjected to exploratory data analysis by finding why there were certain missing values, and how to deal with them. Then, each stock was segmented on the basis of a pre-defined threshold to minimize noise. Linear regression and next-day forecasting was performed on these stocks.

### **Data Source:**
https://uk.finance.yahoo.com/

### **Stocks used:**
The stocks that were worked on were:
1. RMG - Royal Mail PLC
2. NWG - Natwest Group PLC
3. JET - Just Eat Takeaway
4. AHT - Ashford Hospitality Trust

The missing values were first ascertained as to why they were missing. Then, linear regression was used to model and predict future closing price of all four stocks. Segmentation analysis was used to segment each time-series on different time parameters at t = 0.1, 0.2, and 0.4. Then, next-day forecasting was used to forecast the next day closing price of a stock by predicting it as its previous day closing price. Next-day forecast was then plotted along with its residuals. Various descriptive statistics were performed on these four time-series and their results are plotted in each py file.

### **Results:**
Same amount of missing values were found in all four stocks, and the missing values were due to the fact of being a weekend (Sat-Sun) or a bank holiday. The plots for linear regression and next-day forecast are plotted in their respective ipynb files.

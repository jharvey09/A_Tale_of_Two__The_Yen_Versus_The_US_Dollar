# A Yen Into The Future Using Time Series Analysis
The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.
In this assignment, you will test the many time-series tools that you have learned in order to predict future movements in the value of the Japanese yen versus the U.S. dollar.
You will gain proficiency in the following tasks:

# Time Series Forecasting
The Following has been utilized in analysing historical data for the Yen:
1) Hodrick-Prescott Filter
2) ARMA Model
3) ARIMA Model
4) GARCH

# Files
Use the following starter code to complete this assignment.
Note: The starter code shows example calculations and figures to use as a guide. However, your actual output may differ depending on the code and data used.
Time-Series Starter Notebook
Linear Regression Starter Notebook
Yen Data CSV File

# Questions Asked
1) Based on your time series analysis, would you buy the yen now?
2) Is the risk of the yen expected to increase or decrease?
3) Based on the model evaluation, would you feel confident in using these models for trading?

# Steps Taken
1) Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
2) Forecasting Returns using an ARMA Model.
3) Forecasting the Settle Price using an ARIMA Model.
4) Forecasting Volatility with GARCH.

# Linear Regression Forecasting
![image](https://user-images.githubusercontent.com/80294571/127751009-6bc924c5-dd76-4420-b5cc-cd17c1010a6c.png)




# Conclusion
In this particular model, The out of sample performed slightly better than the In-sample data. The Out-of-sample had a root mean squared error of 0.415, while the in-sample data has an RMSE of .596. From this data I would say the model has a "good" fit.


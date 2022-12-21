# Time-Series-analysis-Japanese-Yen-vs-US-dollars
![image](https://user-images.githubusercontent.com/91350558/209006087-c79fdb63-8c75-42fd-a464-b4b9dcdbd717.png)


## Description

When conducting international commerce, multinational corporations' financial divisions frequently deal with foreign currency transactions. 
As a result, they are always on the lookout for anything that may assist them in better understanding the future direction and risk of various currencies. 
Hedge funds, too, are eager to find anything that would offer them a consistent edge in anticipating currency changes and avoiding large adverse swings.
In this repository, I have used Dollar-Yen futures contracts to try time-series techniques in order to forecast future movements and volatility 
in the value of the Japanese yen vs the US dollar.

Through this project I have gained proficiency in the following tasks:

1. Time Series Forecasting

2. Linear Regression Modeling

3. Risk Forecasting


Files

[Time-Series Analysis Notebook](https://github.com/jsaumya20/Time-Series-analysis-Japanese-Yen-vs-US-dollars/blob/main/time_series_analysis.ipynb)

[Linear Regression Notebook](https://github.com/jsaumya20/Time-Series-analysis-Japanese-Yen-vs-US-dollars/blob/main/regression_analysis.ipynb)

[Yen Data CSV File](https://github.com/jsaumya20/Time-Series-analysis-Japanese-Yen-vs-US-dollars/blob/main/yen.csv) 

** Steps taken:**

#### Time-Series Forecasting

I loaded historical Dollar-Yen exchange rate futures data into this notebook and used time series analysis and modeling to see if there is any predicted trend.

Follow the steps outlined in the time-series starter notebook to complete the following:

1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).

2. Forecasting Returns using an ARMA Model.

3. Forecasting the Settle Price using an ARIMA Model.

4. Forecasting Volatility with GARCH.

Use the results of the time series analysis and modeling to answer the following questions:

1. Based on your time series analysis, would you buy the yen now?

2. Is the risk of the yen expected to increase or decrease?

3. Based on the model evaluation (coefficients, p-values, RMSE, etc.), would you feel confident in using these models for trading?

#### Linear Regression Forecasting

In this notebook, I have build a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns.


1. Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.


**So lets find out does this model perform better or worse on out-of-sample data compared to in-sample data?**

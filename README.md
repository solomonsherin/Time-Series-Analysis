# Time-Series-Analysis
Homework 10- Fintech Bootcamp

# Unit 10—A Yen for the Future

## Background

The financial departments of large companies often have to make foreign currency transactions when doing international business, while hedge funds are also interested in anything that will provide an edge in predicting currency movements. Hence, both are always eager to gain a better understanding of the future direction and risk of various currencies. 

In this assignment, we were asked to test the many time series tools that you have learned in order to predict future movements in the value of the Canadian dollar versus the Japanese yen.

1. Time series forecasting
2. Linear regression modelling

#### Time-Series Forecasting

In this notebook, we used historical CAD-JPY exchange rate data and apply time series analysis and modelling to determine if there is any predictable behaviour.

1. Plotting the Settle price to check for long or short-term patterns.
   
2. Decomposition using a Hodrick-Prescott filter (decompose the settle price into trend and noise).

3. Forecasting returns using an ARMA model.

4. Forecasting the exchange rate price using an ARIMA model.

5. Forecasting volatility with GARCH.



#### Linear Regression Forecasting

In this notebook,we were asked to build a Scikit-Learn linear regression model to predict CAD/JPY returns with *lagged* CAD/JPY futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

1. Data preparation (creating returns and lagged returns, and splitting the data into training and testing data)
2. Fitting a linear regression model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

#### The Results are explained in the ipynb files. resulting in Decision Making Answers.
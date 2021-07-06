# Timeseries and Linear Regression

## Timeseries

In this notebook, I loaded historical Dollar-Yen exchange rate futures data and applied time series analysis and modeling to determine whether there was any predictable behavior.

- **Return Forecasting: Initial Time-Series Plotting**
![](https://raw.githubusercontent.com/bhatt11z/A-Yen-for-the-Future/main/Screen%20shots/Screenshot%202021-07-05%20at%209.18.27%20PM.png)

- **Decomposition Using a Hodrick-Prescott Filter**
![](https://raw.githubusercontent.com/bhatt11z/A-Yen-for-the-Future/main/Screen%20shots/Screenshot%202021-07-05%20at%209.20.47%20PM.png)

- **Forecasting the Settle Price using an ARIMA Model**
![](https://raw.githubusercontent.com/bhatt11z/A-Yen-for-the-Future/main/Screen%20shots/Screenshot%202021-07-05%20at%209.22.33%20PM.png)

- **Volatility Forecasting with GARCH**
![](https://raw.githubusercontent.com/bhatt11z/A-Yen-for-the-Future/main/Screen%20shots/Screenshot%202021-07-05%20at%209.24.20%20PM.png)


## Linear Regression

In this notebook, I built a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

- **Lagged Return**
![](https://raw.githubusercontent.com/bhatt11z/A-Yen-for-the-Future/main/Screen%20shots/Screenshot%202021-07-05%20at%209.35.45%20PM.png)

- **Linear Regression Model**
![](https://raw.githubusercontent.com/bhatt11z/A-Yen-for-the-Future/main/Screen%20shots/Screenshot%202021-07-05%20at%209.37.36%20PM.png)



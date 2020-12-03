# Time-Series-Analysis-for-Turnover
Time Series Analysis for Turnover of industries in Australia

This notebook is a summary of common time series analysis methods used to forecast turnover of all industries in Australia(retail.xlsx).

Contributors: Wong Hui Hui, Kimberly Chan Yuan Lin, Josiah Loke Wai Kit

We first explored the additive and multiplicative assumptions and see if they hold true for the turnover dataset. We concluded that multiplicative assumption would work the best for this dataset. We then tried various methods under different assumptions to see if our hypothesis holds true. Performance of models compared using the RMSE of the test set(last 30% of data).

Methods used under Additive assumption:

1) Simple Exponential Smoothing(SES)
2) Double Exponential Smoothing(DES)
3) Triple Exponential Smoothing(TES)

Methods used under Multiplicative assumption:

1) DES
2) TES

Methods used under Damped Additive assumption:

1) DES
2) TES

Methods used under Damped Multiplicative assumption:

1) TES

Linear Regression:

1) Naive Linear Regression
2) Linear Regression with last N data and the average of last year around the same month (MA)
3) Linear Regression with last N data and the average of last year around the same month (MA) and exponential smoothing
4) Linear Regression with last N data

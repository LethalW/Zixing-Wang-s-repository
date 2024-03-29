# Zixing-Wang-s-repository

Project topic: 
Using Logit machine learning model to predict stock default.

Project Abstract:
Based on China's A-share market, this paper first extracts the stock information of Ping An Bank from 1998 to the end of 2023, then selects part of the data from 2020 to 2023 after screening, and uses the log return function to calculate the logarithmic return rate. On the basis of the mean and standard deviation of the logarithmic return, the 70% quantile of the normal distribution is calculated, and the stock default standard is set up. It is considered that if the stock return increase is greater than var1, it indicates no default, while if it is less than var1, it indicates default. Then, MACD index, OBV index and CCI index were calculated, and the training set and test set of Logit machine learning model were set based on the calculated data, as well as the test set was predicted by logistic regression model. At last, the project evaluated the accuracy and performance of the machine learning model through confusion matrix and ROC curve respectively, and the accuracy of the model reached 99.5%. 

Project background information: 
1)	Value at Risk: Value-at-Risk (VaR) is a common measure used in financial risk management to measure the maximum possible loss of a financial asset or portfolio within a certain time frame. VaR is expressed as a probability, usually defined as the maximum possible loss at a particular confidence level. 
2)	Determine whether the stock is in default: 70% is selected as the confidence interval. After calculating VaR based on previous stock trading data, the maximum loss estimate of 70% confidence interval is obtained, and then compared with the actual stock return rate. If the yield is lower than the maximum loss estimate, it is judged to be a default and marked with 1, and otherwise marked with 0.

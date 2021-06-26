# Unit 10—A Yen for the Future

![Credit card fraudster](https://www.ft.com/__origami/service/image/v2/images/raw/http%3A%2F%2Fcom.ft.imagepublish.prod.s3.amazonaws.com%2F7ca6c4bc-fcae-11e5-b5f5-070dca6d0a0d?fit=scale-down&source=next&width=700)

## Background
The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.
In this assignment, you will test the many time-series tools that you have learned in order to predict future movements in the value of the Japanese yen versus the U.S. dollar.

# Time-Series Forecasting
In my notebook, I loaded historical Dollar-Yen exchange rate futures data and applied time series analysis and modeling to determine whether there is any predictable behavior.

## Questions
1. Based on your time series analysis, would you buy the yen now?
2. Is the risk of the yen expected to increase or decrease?
3. Based on the model evaluation, would you feel confident in using these models for trading?

## Answers
1. Based on my ARIMA 5-day forecast model, I would buy then yen as it's proejcted to rise over the next week. 
2. Based on my GARCH model, the yen is projected to become more volatile over the next 5-days and therefore will be more risky. 
3. I am confident in these models to use as trading tools, while understanding there are a lot of variables that can still impact the outcome of these models. 

# Linear Regression Forecasting

## Questions
1. Does this model perform better or worse on out-of-sample data compared to in-sample data?

## Answers
1. Out-of_sample is 0.596 and in-sample is 0.415, therefore out-of-sample performs better. 
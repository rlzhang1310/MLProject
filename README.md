# MLProject

A stock market predictor created using S&P500 data from the past 5 years

The Machine Learning Model uses a RNN with 2 LSTM layers and 2 dense layers, taking in the last 7 business day percent change of prices from 7 business days ago, and outputs the percent change the next day.
I then iteratively ran the model to predict the percent change in the next 7 days, and found the intergral the percent change to find the net change of price to assign the value of a specific stock.
Using these values that I ran through with every S&P500 stock, I simulated an investment with 100,000 dollars starting with data till 8/29/2023, and validated the data with data on 9/8/2023 (7 business days after).

I used the S&P500(^GSPC) stock as the controlled to visualize the over stock price trend of the S&P500 companies 
The end result was a $358 profit compared to the -$893 loss to S&P500 overall, giving this model making 1.2514% more than simply investing in S&P500

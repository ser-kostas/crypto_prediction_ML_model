# Data-analysis---Crypto Prediction
Using python and machine learning to analyze data regarding Bitcoin for the past 1 years 

In the current repository we are using yfinance to upload the data of Bitcoin for the past year. The past year is calculated based on todays date.

Then we are making some basic data preparation and checks. After that we are running a basic plot to visualise the data. 

Then we create 3 machine learning models to predict the future prices of the Bitcoin. The first model is a basic model that splits the data of the opening prices into 80-20 and make the predictions. Then we are ploting the differences of the predicted and the actual prices. 
The Second model uses the moving avg for 7,14,30 days to remove any extremes and then predicts the future values.
The Third model uses Fibonacci, it calculates the fibonacci prices for a window of 5 days and then uses the prices to predict the future values of the bitcoin.

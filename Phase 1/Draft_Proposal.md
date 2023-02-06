# Amazon Stock Prediction
## Authors: Anuja Yawar, Devarsh Shah
<br>
<br>

The purpose of this project is to built a machine learning model to predict price of Amazon stock based on previous data. Examplary features of the data could be high, low, open,
close etc. In stock trading, the high and low refer to the maximum and minimum prices in a given time period. Open and close are the prices at which a stock began and ended trading in the same period. We will also be considering fundamental parameter such as dividend cash flow liquidity, liability at the given period of time.   
<br><br>
**Source of dataset:** 
<br> We would like to take our data from [Yahoo Finance](https://finance.yahoo.com/quote/AMZN/history?fr=sycsrp_catchall) from year 1997 to 2022. 
<br><br>
**Machine Learning model:** <br>
After researching and reading documentation available online, we learnt that for stock market predicition SVM an LTSM are the best fit models. However, we will verify the same in our project by comparing it with different ML models such as Linear Regression, Ensemble Learning etc..
To optmize the model if will be using techniques likes hyper parameter tuning using GridSearchCV. 
<br><br>
**Deployment:(Experimental)** <br> We will try to deploy model and the analysis of the data into web-app through Java spring-boot frame work using microservice architecture.
<br><br>
**End Goal:** <br> Our main motive is to successfully predict the stock price of amazon considering the previous trends.

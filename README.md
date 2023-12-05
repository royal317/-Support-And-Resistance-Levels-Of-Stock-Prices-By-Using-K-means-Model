#  Support And Resistance Levels Of Stock Prices By Using K-means Model
Unsupervised classifier is when a computer that looks at data (without any labels or 
previous data thus unsupervised) and finds similarities between records and segments 
them according to classification clusters difference. And K-Means is a very popular 
unsupervised machine learning algorithm that I chose to test for the topic. In essence, 
it takes the data and tries to generate K number of groups that we define and groups 
the data based on how close to the center of each cluster K

# Research Methods
Because I want to learn more solutions to identify support/resistance levels in support 
of building intraday investment strategies for analysts/investors, I collect the intraday 
trading of stock price data of any company is publicly available on a website for 
testing.

# Sample selection, data collection
Since intraday data for companies in Vietnam is not publicly available for free on 
popular websites and almost all have a fee to obtain, I decided to access stock price 
data (in a day) of a foreign company, namely Amazon (AMZN), can be accessed for 
free at Yahoo Finance through the yfinance package integrated in the Python 
language. The period selected for the test is June 1, 2023 to June 2, 2023

#  CONCLUSION
It can be seen that the application of the K-Means unsupervised machine learning 
algorithm in determining the given support/resistance levels has produced unexpected 
results and contributed to the stock valuation process as well as investment decision 
making. Besides, the application of this algorithm is only feasible when the review 
dataset has less than 100 data points, which means it should be used mainly for the 
purpose of reviewing intraday investment strategies. When the dataset we consider is
larger than the other, we should consider changing our approach and using more 
advanced and complex models such as Neural Networks.
Also, as mentioned, the use of this algorithm is not only for determining 
support/resistance levels for stocks but it can also be used for cryptocurrencies. 
However, in the implementation process, it is necessary to pay attention to the time 
zone of each asset class to facilitate an objective and accurate review.

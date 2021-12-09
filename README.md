
# Bitcoin price prediction using tweet sentiment analysis using Bag of words model

# Introduction
Sentiment Analysis can be defined as the process of analyzing text data and categorizing them into Positive, Negative, or Neutral sentiments. Emotions such as anger, disgust, fear, happiness, sadness, and surprise can also be detected. Sentiment Analysis is used in many cases like tracking social media conversations, product reviews, feedbacks, survey responses, etc. which allows companies to understand the customer's emotions better and thus meet their needs.

# About the problem statement
Bitcoin has become a very popular investing instrument in recent times with the promotion of decentralized digital currency without a central bank or single administrator. This leads to price fluctuations, which can also be attributed to positive or negative twitter conversations around bitcoin. Here, I attempt to predict bitcoin price movement by assessing twitter sentiment.

# Methodology
Bitcoin tweets data is used to predict bitcoin prices. 2 files containing bitcoin tweets data have around 8,00,000 and 10,00,000 rows each. Due to the sheer volume of data, deep learning approaches are used. For sentiment extraction from tweets, bag of words approach is used. Extensive data wrangling is done to manipulate the data into the format useful for prediction. Every second we have around 40 tweets on bitcoin in the data. Bitcoin price might not fluctuate very much every second with any useful predictive ability, so I combine all tweets into per minute and check for price fluctuations every minute. 

Method 1: Using a Multi layer perceptron stacking dense layers.
#
Method 2: Using LSTM layer by using sequence modelling using timesteps as 60

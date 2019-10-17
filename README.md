# predictit_tweets

This project focuses on building a model to calculate the number of weekly tweets posted by the Twitter account @realdonaldtrump. The base model explored is a Poisson regression model for the daily number of tweets given previous days. After observing the tweets for each day, we can use the model to simulate the total number of tweets accumulated over a given week. Based on different paths, we are then estimating the probability of getting a number of tweets at the end of week. 

The analysis can be found in analysis.ipynb.

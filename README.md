The Problem

Twitter  is a  popular social media platform and has become an important communication channel in times of emergency.Our problem is to  distinguish tweets which announces a real disaster from other tweets. Basically predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.

Dataset
Open access to a dataset hosted on Kaggle of 10,000 tweets that were hand classified

Real or Not? NLP with Disaster Tweets

train.csv [columns: id, keyword, location, text, target]

test.csv [columns: id, keyword, location, text]

Columns

id - a unique identifier for each tweet

text - the text of the tweet

location - the location the tweet was sent from (may be blank)

keyword - a particular keyword from the tweet (may be blank)

target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)


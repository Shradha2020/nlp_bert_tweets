# The Problem

Twitter  is a  popular social media platform and has become an important communication channel in times of emergency.Our problem is to  distinguish tweets which announces a real disaster from other tweets. Basically predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.

## Dataset

Open access to a dataset hosted on Kaggle of 10,000 tweets that were hand classified

Real or Not? NLP with Disaster Tweets

train.csv [columns: id, keyword, location, text, target]

test.csv [columns: id, keyword, location, text]

## Columns

id - a unique identifier for each tweet

text - the text of the tweet

location - the location the tweet was sent from (may be blank)

keyword - a particular keyword from the tweet (may be blank)

target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

# Model Comparisons on Accuracy, Precision, Recall and F1 Scores

![image](https://user-images.githubusercontent.com/71346494/142354043-2023afe4-e5ec-4bbf-9054-f3098b9994c8.png)

![image](https://user-images.githubusercontent.com/71346494/142354102-cd9b12d2-9963-425b-8c90-155c978102dc.png)

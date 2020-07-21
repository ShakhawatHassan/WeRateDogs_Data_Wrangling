# Data Wrangling on WeRateDogs
## by Shakhawat Hassan

![Image of Dog](https://pbs.twimg.com/media/EYa1LVSWkAczgk2?format=jpg&name=small)

## Summary of Findings
> There are more favorite tweets than counts of a retweet on WeRateDogs. This means people are favoriting a picture of a dog than they are retweeting that tweet. Top names are A (unrecorded name), Charlie, Penny, Lucy, and Tucker. The stage of Pupper has the highest number of dogs among all other stages. 

## Tools Used for this Project
  - Packages: Anaconda, Conda
  - Libraries: Pandas, NumPy, Matplotlb, Seaborn 
  - API: Tweeter API or Tweepy
  - Web Application: Jupyter Notebook
  - Programming Language: Python 3



## Web Scraping
### Tweeter's API Terms

[*Query Twitter API for each tweet in the Twitter archive and save JSON in a text file.
 These are hidden to comply with Twitter's API terms and conditions*]
 consumer_key = 'HIDDEN'
 
 consumer_secret = 'HIDDEN'

access_token = 'HIDDEN'

access_secret = 'HIDDEN'

auth = OAuthHandler(consumer_key, consumer_secret)

auth.set_access_token(access_token, access_secret)

api = tweepy.API(auth)*

## Sources
Datasets: twitter.com/dog_rates

Image: twitter.com/dog_rates/status/1262895960432181249/photo/1


# Wrangle-Analyze-Data
## by Shakhawat Hassan

## Dataset


## Summary of Findings


## Tools Used for this Project
  - Packages: Anaconda, Conda
  - Libraries: Pandas, NumPy, Matplotlb, Seaborn 
  - API: Tweeter API or Tweepy
  - Web Application: Jupyter Notebook
  - Programming Language: Python 3





[*Query Twitter API for each tweet in the Twitter archive and save JSON in a text file.
 These are hidden to comply with Twitter's API terms and conditions*]
 consumer_key = 'HIDDEN'
 
 consumer_secret = 'HIDDEN'

access_token = 'HIDDEN'

access_secret = 'HIDDEN'

auth = OAuthHandler(consumer_key, consumer_secret)

auth.set_access_token(access_token, access_secret)

api = tweepy.API(auth)*

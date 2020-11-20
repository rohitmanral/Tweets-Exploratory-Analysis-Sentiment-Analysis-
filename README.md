# Tweets-Sentiment-Analysis


<center> <h1>Tweets Exploratory Analysis </h1> </center>

<p align="center">
  <img width="260" height="150" src="https://miro.medium.com/max/2560/1*sDa7Oqnh-zRXPPewKZid4g.png">
</p>



## Overall Goal
For this task, I will be collecting some tweets, and conducting a data analysis along the lines of the one of Donald Trump's & Scott Morrison's tweets.

## Data
I will collect 400 tweets from 2 different Twitter users, 200 from each.  You should try to find two users where you would expect there to be some noticeable differences in their tweets.

## Task
* Use pandas to plot the posting times of the tweets for the two users; the aim of the plot is to distinguish the two users.
* Use pandas to construct a bar chart of the proportions of tweets for each of the two users that contain pictures or links.
* Use pandas to construct a histogram of the number of hashtags in tweets for each of the two users.
* Calculate the log odds ratio (check here for an example) for each word used in the set of tweets, and list the 20 words most strongly associated with each of the two users.
* Use the nltk vader module to calculate the sentiment of each tweet, and then for each of the two users, calculate the average 'compound' sentiment for all their tweets.
For this last point: [vader](https://github.com/cjhutto/vaderSentiment) is a sentiment analysis package that is tailored to social media.  You can use [NLTK](https://www.nltk.org/) in the Colab Jupyter environment.  You will need to !pip install tweepy; once you have imported nltk, you will have to download the vader lexicon, and the error message NLTK gives you will explain how.  The relevant part of the module is [nltk.sentiment.vader (https://www.nltk.org/_modules/nltk/sentiment/vader.html).  You should be able to straightforwardly run the sample Python code from the [vader github repo](https://github.com/cjhutto/vaderSentiment) in your notebook.

(If you want to learn more about NLTK and look at examples of its use, there's a very hands-on book.) 

# TWITTER STREAMING APP

**We’ll create a simple application that plots out the popularity of tags associated with incoming tweets streamed live from Twitter.**

To do all of this :

* We first need to create a Twitter Developer Account to get our access codes. Via this link : apps.twitter.com

  * PS : if you don't have a twitter account, create one

  * We need 4 codes which are : **API KEY, API KEY SECRET, ACCESS TOKEN, ACCESS TOKEN SECRET**

  * The ACCESS TOKEN is going to be used to make the API request on our twitter account ! MAKE SURE YOU DON’T SHARE IT WITH ANYONE

  * MAKE SURE YOU HAVE THESE 4 SAVED ON A TEXT FILE, WE ARE GOING TO USE THEM FURTHER

* Then you’ll need to install the tweepy library as well as matplotlib and seaborn. Via your CLI, Enter :

  * pip3 install tweepy : which is the library which connects tweeter and python

  * pip3 install matplotlib : python visualization library

  * pip3 install seaborn : python visualization library

* Our next task is to write a script that will connect to Twitter for streaming, this will be a .py file that we will call later on ( you will find it as **TweetRead.py** )

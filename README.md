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

  * **NOTE** : if you are facing this kind of errors when you run the TweetRead.py file such as :
  
    * ImportError: cannot import name 'Stream' from 'tweepy',  or

    * ImportError: cannot import name 'StreStreamListeneram' from 'tweepy.streaming'

    * Please do the following :

      * pip uninstall tweepy : to uninstall the current version of tweepy

      * ip install tweepy==3.10.0 : to install the 3.10.0 stable version

* If the TweetRead.py ran successefully, make sure you change the port number to another number than 5555, for example : 9998, just to not have a problem of : PORT ALREADY USED

* One last import : pip3 install pandas

* Restart the machine

* Open two terminals, one to start a jupyter notebook to run TwitterStreamingApp.ipynb and the other to run the TweetRead.py by executing this line of cammand : python3 TweetRead.py when you read in the jupiter notebook a note that says : now run TweetRead.py

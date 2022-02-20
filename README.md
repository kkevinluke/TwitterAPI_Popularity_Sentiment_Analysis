# TwitterAPI_Popularity_Sentiment_Analysis
Determines the overall sentiment of the latest tweets on a keyword. Preferably on popular figures.

The Twitter API used here parses tweets using the Tweepy API and a geocode in the UK with a radius that encompasses all of the UK.
The tweets and other metadata are indexed off of the JSON response to be converted into a dataframe.
Then mutiple NLP techniques are used to visualize the spread, nature and sentiment of the tweets. 
The end result considers all the thousands of tweets in the last month and gives a result of the no. of positve and negative tweets for that keyword.

(Please experiment, using own keyword and different radius lengths
I personally found intruiging result for game titles as keyword in different locations.)

To retrieve geocode for you desired locations. I used the link below.
https://www.mapdevelopers.com/geocode_tool.php

geocode=(lat,lon,xkm)  ex. geocode=(51.3358,-3.345,100km)
The geocode in the tweepy API should appear as shown, "no spaces".

Enjoy. 

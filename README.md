# Big-Data-proj
CSE 482 group proj

# Requirements
- Download the streamed tweets:
	- https://drive.google.com/drive/folders/1dis1b8tN8BBJyZtFeefQMqPdLU5gPgii?usp=sharing
- Download the filtered tweets (to avoid running the preprocessing code again):
	- https://drive.google.com/drive/folders/1vnosz7wREN4BuyUrEoOpFvljc_zfHgQA?usp=sharing
- Run the notebooks using Jupyter Notebook and Python 2
- Install these modules on your machine:
	- testblob

# Instructions on How to Use
- First, run the preprocessing_tweets.ipynb notebook to process
	the streamed tweets. Skip the first block as that was 
	what was used to streamed the tweets.
- The following steps create directories of the dates of the
	tweets when they were streamed and creates files for 
	each country in the United States with all the tweets
	per state per day is listed.
- Next, run the sentiment_analysis_classifier.ipynb notebook to
	classify the sentiment of the tweets. This notebook uses
	the textblob library to classify the words in each tweet
	to evaluate a tweet's overall sentiment.
- The end of the notebook generates a time series for all of days
	of tweets by states of the net daily sentiment of BTS.

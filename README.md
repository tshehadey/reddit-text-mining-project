# ADS509 Applied Text Mining
### Authors: Madeline Chang, Jose Guarneros Padilla, Tysir Shehadey

## Abstract:
Using the RedditAPI, this project utilizes both supervised and unsupervised machine learning models to explore data from the "science" and "technology" subreddits.

## Goals:
1. Discern words and phrases that are unique to the science subreddit and the technology subreddit.
1. Create a classification model that accurately predicts the subreddit a corpus of text was pulled from.

## Data Sources:
Raw data was scraped using the RedditAPI, which allows users to pull text from posts within a specific subreddit. The data in this project focuses on the "science" subreddit and the "technology" subreddit.

## Data Exploration:
The raw text was processed by making all letters lowercase, removing unwanted items (such as urls, markdown formatting, punctuation, and stopwords), and lemmatizing all tokens. The frequency of words was studied, along with the most common words per subreddit.

## Future Enhancements:
For further research, more hyperparameter tuning and a wider range of classification models should be studied. In addition, new scrapes of data could be used to track the sentiment and most common topics discussed on each subreddit over time.

# References
reddit.com: api documentation. (n.d.). Www.reddit.com. https://www.reddit.com/dev/api/

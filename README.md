
## Introduction
This project scrapes twitter to create a searchable and sortable table of news-related tweets from various users. 

This project solves the following problems:
1. How to stay ahead of the news without endless scrolling. 
2. How to determine what news articles are receiving more attention. 
3. How to understand today's news in the context of news from the past, all the way back to the mid 2000s. 

## How to use
1. Go to src/
2. Run scrape_tweets.py. Note that the file users.csv contains the twitter users you want to scrape. In this case, it's biorxiv and medrxiv. This will produce output as csv files that sit in data/.
3. Run news_history.ipynb to get the updated table. 
4. To get the html file, run jupyter nbconvert --to html --no-input news_history.ipynb

## Possible extensions
Any twitter username is fair game. It just needs to be added to the users.csv file. 

## Acknowledgements
The [snscrape project](https://github.com/JustAnotherArchivist/snscrape), for their amazing work that makes this type of data curation possible. If anything, I hope this project brigs awareness to their work. I also hope that my project contibutes to theirs by providing an example of how to use their python package, which has not been documented yet as their command line interface has. 
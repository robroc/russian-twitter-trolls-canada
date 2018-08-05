# An analysis of Russian troll tweets aimed at Canadians

This is the Python code used to analyse the 3 million tweets from Russian troll farm Internet Research Agency, published by [FiveThirtyEight](https://github.com/fivethirtyeight/russian-troll-tweets).

Read the story here: [Data sheds light on how Russian Twitter trolls targeted Canadians](http://www.cbc.ca/news/canada/russian-twitter-trolls-canada-targeted-1.4772397)

This code isolates tweets aimed at Canadians and analyzes broad statistics on them.

The resulting dataset of Canada-specific tweets is in the file `troll_tweets_canada.csv`

The code is in the Jupyter Notebook file (.ipynb). It requires the pandas and matplotlib libraries. Some natural language processing is done with the nltk library.

To run the entire code, you will need to download the original data files from the [FiveThirtyEight repo](https://github.com/fivethirtyeight/russian-troll-tweets).

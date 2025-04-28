# Customer-sentiment-analysis
Objective
As a Data Analyst at Amazon, the objective of this project was to gauge customer sentiment towards the iPhone 15 128GB model. By scraping customer reviews from Flipkart, cleaning and preprocessing the data, and performing sentiment analysis, the project aims to uncover insights about public perception and customer satisfaction.

Tools & Libraries Used:

Data Handling: pandas, numpy

Web Scraping: selenium, BeautifulSoup, requests

Text Processing & Sentiment Analysis: nltk, TextBlob

Visualization: matplotlib, seaborn

Key Steps:

Scraped 100 reviews (username, rating, review text) using Selenium and BeautifulSoup.

Data Cleaning: Removed duplicates, handled missing values, preprocessed text (lowercasing, tokenization, stopwords removal, lemmatization).


Sentiment Analysis:

Polarity scoring via TextBlob.

Classified reviews as Positive (polarity ≥ 0.1) or Negative (polarity < 0.1).


Data Analysis & Visualization:

Sentiment distribution, rating vs sentiment analysis.

Created word clouds to highlight frequent words.

How to Run:

pip install pandas numpy matplotlib seaborn selenium  beautifulsoup4 textblob nltk requests

Run the Customer Sentiment Analysis.ipynb notebook to replicate the analysis.



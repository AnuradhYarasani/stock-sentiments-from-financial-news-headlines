# Stock sentiment Analysis
Sentiment analysis on natural language sentences can increase the accuracy of market prediction because financial markets are influenced by investor sentiments.

## Table of Contents

- [About](#about)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Acknowledgments](#Acknowledgments)

## About

Stock sentiments are determined from financial headlines scraped from the web.
The idea is that the averaged value may give valuable information for the overall sentiment of a stock for a given day (or week if you decide to average over a week’s news). What makes it easier to parse the website is that you simply have to add the stock ticker at the end of this url ‘https://finviz.com/quote.ashx?t=’ I hope you find this useful. All code is available in this Python Notebook. Of course, it is now up to you to decide what to do with the sentiment scores obtained! You can try doing machine learning with it if you want!

## Demo
 
![image](https://github.com/AnuradhYarasani/stock-sentiments-from-financial-news-headlines/assets/113980248/cbbb4de8-fd2e-4dee-adb3-d6495cdfb95c)

## Features

List the key features of this project:
- Feature 1: hourly sentiments for a stock.
- Feature 2: daily sentiments for a stock.
- Feature 3: monthly sentiments for a stock.

## Installation

- !pip install flask
- !pip install nltk
- !pip install urllib3
- !pip install bs4
- !pip install plotly

## Acknowledgments

I would like to express our gratitude to the following individuals, organizations, and resources for their invaluable contributions and support in the development of this stock news sentiment analysis project:

- **Financial Data Providers**: We acknowledge the contributions of financial data providers, whose services and APIs made it possible to access and analyze real-time stock market data and news.

- **Natural Language Processing (NLP) Libraries**: Our project relies on the powerful NLP libraries and tools, including NLTK, spaCy, and scikit-learn, which played a crucial role in text analysis and sentiment classification.

- **Machine Learning Frameworks**: We extend our thanks to the creators of machine learning frameworks such as TensorFlow and scikit-learn, which enabled us to build robust sentiment analysis models.

- **Open Source Community**: We appreciate the efforts of the open-source community for creating and maintaining various software libraries, plugins, and tools that enhanced our project.

- **Financial News Sources**: We are grateful to the financial news sources and publications that provide valuable data and news updates, which were essential for our analysis.


# Web-crawling-and-news-virality-prediction
Crawling online news sites and anticipating the likelihood of its virality. This is an example of web scraping and crawling with BeautifulSoup4 python package. I scraped news titles and their descriptions from online news sites and predicted whether a given news article is likely to be viral or not.

Format: ![Alt Text](https://www.google.com/imgres?imgurl=https%3A%2F%2Fmedia-exp1.licdn.com%2Fdms%2Fimage%2FC511BAQFI91Hv9niLOA%2Fcompany-background_10000%2F0%3Fe%3D2159024400%26v%3Dbeta%26t%3DNs90SQCpixGoIU4KDSzc1gNhhnG24v_hntJ_mQSz_V4&imgrefurl=https%3A%2F%2Fin.linkedin.com%2Fcompany%2Fviral-news&tbnid=uOo15J_cgkyRnM&vet=12ahUKEwiwmvTFzI3pAhX5x3MBHcteC1gQMygMegUIARCdAg..i&docid=CbTjMBlAibR7cM&w=700&h=400&q=viral%20news&client=ubuntu&ved=2ahUKEwiwmvTFzI3pAhX5x3MBHcteC1gQMygMegUIARCdAg)


## Requirements
-[BeautifulSoup](https://pypi.org/project/beautifulsoup4/) 

Beautiful Soup is a Python package for parsing HTML and XML documents. It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.
Use the package manager pip to install BeautifulSoup .
For Python3:
```
pip install beautifulsoup4
```

-[Requests](https://pypi.org/project/requests/)

Requests is a Python to make HTTP requests simpler and more human-friendly. 
```
pip install requests
```

-[WordCloud](https://pypi.org/project/wordcloud/)

Word Cloud is a data visualization technique used for representing text data in which the size of each word indicates its frequency or importance.
```
pip install wordcloud
```

## Getting Started
This project is divided into five steps:

### 1. News Scraping

The objective of this step is to scrap webpages and create a dataframe with title and description for each news url. This is done using [BeautifulSoup](https://pypi.org/project/beautifulsoup4/) and [Requests](https://pypi.org/project/requests/) libraries for Python.

### 2. Cleaning Data

This step involves making text lowercase, removing punctuatin,removing stopwords,removing numerical values, tokenization, lemmatization. Python libraries [nltk](https://www.nltk.org/) and [re](https://docs.python.org/3/library/re.html) have been used here to clean the text.

### 3. Document-Term Matrix

A DTM is a matrix that describes the frequency of terms that occur in a collection of documents where every row will represent a different document and every column will represent a different word. This is achieved with the help of scikit-learn's [CountVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html).

### 4. Data Visualization


### 5. Prediction

As test set I have used both trending and normal urls from India Today's website. A prediction of 0 






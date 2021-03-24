# Multi class classification using BERT and Tensorflow
Bidirectional Encoder Representations from Transformers or BERT for short is a very popular NLP model from Google known for producing state-of-the-art results in a wide variety of NLP tasks.
The importance of Natural Language Processing (NLP) is profound in the Artificial Intelligence domain. The most abundant data in the world today is in the form of texts and having a powerful text processing system is critical and is more than just a necessity.
In this article we look at implementing a multi-class classification using the state-of-the-art model, BERT.

# About Dataset 
Dataset downloaded from: (https://www.kaggle.com/rohan9889/predict-news-category)
FEATURES:
STORY: A part of the main content of the article to be published as a piece of news.
SECTION: The genre/category the STORY falls in.
There are four distinct sections where each story may fall in to. The Sections are labelled as follows:
Politics: 0
Technology: 1
Entertainment: 2
Business: 3

# Train Dataset
STORY: A part of the main content of the article to be published as a piece of news.
SECTION: The genre/category the STORY falls in.

Table	| Total Rows | Total Columns
------|------------|--------------
Sheet1 |	7628| 	2

# Test Dataset
STORY: A part of the main content of the article to be published as a piece of news.
Table | Total Rows |	Total Columns
------|------------|---------------
Sheet1|	2748|	1


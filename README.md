# **Analysing Stock price using Sentiment analysis**

## **Project Description**
In this project, we will generate investing insight by applying sentiment analysis on posts from the social media site [Stock Twits](https://en.wikipedia.org/wiki/StockTwits) website. Using  natural language processing technique, to understand the emotion behind the headlines and predict whether the market feels good or bad about a stock.\
The aim of this project to build deeplearning model to classify the sentiment message for stocktwits.\
The datasets used in this project are raw JSON files for the twits text messages  from [Stock Twits](stocktwits.com), a popular platform dedicated to investors and traders, entrepreneurs.



### **Installation**
```
import json
import nltk
import os
import random
import re
import torch
from torch import nn, optim
import torch.nn.functional as F
nltk.download('punkt')
nltk.download('wordnet')
from string import punctuation
from nltk.tokenize import word_tokenize
```

## **Twits Pre-processing**

Pre-process each of the twits in our dataset, collected by filtering on ticker symbols.\
We performed text processing like removing punctuation and HTML tags and making everything lower-case.Then clean up by removing stop words and normalizing the text.\
We used tekonize techniques to split the text, and the bag of word for counting the words, the term frequency to measure the occurance of the word or the terms in the message.\
Further, updating vocabluary by removing filterd words, then balancing the classes to help our network learn appropriately.


## **Implement the text classifier**


## **Training**

We build the generator to loop through our data, and pass our sequence as batches.

## **Training and validation**

In this section We will split our data set into traing and vaildation.\
Then train our neural network.

## **Prediction**

We trained the model, and we can make a predictions, then we used this model to track the sentiments of various stocks by predicitng the comming twits

## **Testing**

Finally e used the prediction, and we apply it to stream of twits, to obtain the stock universe score stream.


## **issues**


## **Contributing**

For major changes, please open an issue. First discuss what you would like to change.
please make sure to update tests as appropriate

## **Licence**
```
Copyright (C) 2004 David Gabriel
```



**Further reading**

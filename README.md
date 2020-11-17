# **Analysing Stock price using Sentiment analysis**

## **Project Description**
In this project, we will generate investing insight by applying sentiment analysis on posts from the social media site [Stock Twits](https://en.wikipedia.org/wiki/StockTwits) website. Using  natural language processing technique, to understand the emotion behind the headlines and predict whether the market feels good or bad about a stock.\
The aim of this project to build deeplearning model to classify the sentiment message for stocktwits.\
The datasets used in this project are raw JSON files for the twits  from [Stock Twits](stocktwits.com), a popular platform dedicated to investors and traders, entrepreneurs.



**Installation**
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


**issues**


**Contributing**



**Licence**




**Further reading**

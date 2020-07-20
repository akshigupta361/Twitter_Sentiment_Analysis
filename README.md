# Twitter Sentiment Analysis

# Project Aimed:
Twitter sentiment analysis allows you to keep track of what's being said about your product or service on social media, and can help you detect angry customers or negative mentions before they turn into a major crisis. The aim of the project is to analyze the sentiment of tweets. Through, that sentiment we are trying to analyze what is the mood of the person while tweeting. We can also check the product reviews by using this sentiment analysis.

# Pre-Requisites:
Basic about Python3
Some of the Python Libraries
1.  numpy           
2.  pandas          
3.  seaborn         
4.  sklearn         
5.  matplotlib      
6.  nltk            

# Installation:
There are some steps for installation
1.  Install Python3.            
2.  Install Jupyter Notebook.   
3.  Install all the libraries above mentioned by using "pip install library_name".
4.  Download the project. Run it in your system.

# Dataset:
In the given dataset there are following columns such as tweets and labels. In the dataset, those who positive response are mentioned with a label "1" and those who are not with"0".

Note: The dataset is downloaded from Kaggle: "https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech".

# Algorithm:
As the data is structured and after analyzing the dataset I came to know that we can use classifier in this project. So the classifier used in this is Naive Bayes, using sklearn the naivebayes model is imported. In this seaborn library that uses matplotlib is used to plot graphs and pandas is used for reading the dataset. 
I am getting 93% accuracy in this project through Naive Bayes.

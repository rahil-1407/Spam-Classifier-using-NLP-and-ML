<h1 align="center">
  <br>
  <a href="https://github.com/ShubhamPy/Spam-Classifier"><img src="https://github.com/rahil-1407/Spam-Classifier-using-NLP-and-ML/blob/main/Demo%20Images/logo.jpg" alt="SpamClassifier"></a>
  <br>
  SpamClassifier
  <br>
</h1>
<h4 align="center">In this project I build a model for classifying the SMS/Email into spam or ham through the Machine Learning Algorithms and NLP Models.</h4>

## What It Does: 
<p align="center">
  <br>
  <img src="https://github.com/rahil-1407/Spam-Classifier-using-NLP-and-ML/blob/main/Demo%20Images/Text%20Classifier.jpg">
</p>
 
## How It Does:
Imported datset using pandas library. Then did some Data Cleaning and Preprocessing using re and nltk library. Created Bag of Words Model. Kept 20% of the data for Testing.
Trained the model using Naive Bayes Classifier.
<p align="center">
  <br>
  <img src="https://github.com/rahil-1407/Spam-Classifier-using-NLP-and-ML/blob/main/Demo%20Images/modelLearning.png">
</p>

## Prerequisites:
-  `Python`
-  `scikit-learn` / `sklearn`
-  `Pandas`
-  `NumPy`
-  `matplotlib`
-  `NLP`
-  An environment to work in - something like `Jupyter` or `Spyder`

## Dataset:
The SMS/Email Spam Collection is a set of SMS tagged messages that have been collected for SMS/Email Spam research. 

> You can collect raw dataset from [here](https://github.com/rahil-1407/Spam-Classifier-using-NLP-and-ML/blob/main/SMSSpamCollection).

The files contain one message per line. Each line is composed by two columns:
- `Class`- contains the label (ham or spam) 
- `Message` - contains the raw text.

## Components:
-  Use Bag of Words Model for converting text 
-  Use Multinomial Naive Bayes Algorithm for training. When data is discrete Multinomial NB is used.
-  Use stopwords from nltk library to remove stopwords like (he, she, is, or)in english.

## Future Scope:
- Adding this feature in a dynamic website which supports contact-us typo feature.
- Show live user inputs for Ham and Spam  .

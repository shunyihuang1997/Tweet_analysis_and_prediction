# Covid-19 Tweet Analysis & Prediction
Data from https://www.kaggle.com/datatattle/covid-19-nlp-text-classification. 

## 1) Data pre-processing

- Combined two dataset into one
- Remove useless information in each column
- Encode label
- Convert all the text into lower case
- Remove stopwords (sklearn)
- Re,pve white space, alphabetical characters, numbers, punctunation
- Remove rare words (infrequent words)
- Lemmatization



## 2) Data Visualization
- Word cloud feature
- Show the top 25 most frequent words
- check how the label go as time passes by



## 3) Feature Engineering
- Use count vectorizer to convert the tweet to a matrix of token counts
- User TFIDF vectorizer to convert the tweet to char, word, n-gram level


## 4) Naive Bayes Classification
- char, word, n-gram levels of NB classification


## 5) Random Forest Classification
- char, word, n-gram levels of RF classification



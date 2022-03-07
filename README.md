# tweeter_sentiment_analysis
![79592twitter](https://user-images.githubusercontent.com/79353291/156964344-845f394f-9d6f-46ef-b37d-2733727db16e.jpeg)
* [Notebook for this analysis](https://github.com/raminstad/tweeter_sentiment_analysis/blob/main/Tweeter_Sentiment_Analysis.ipynb)
# Analysis Objectives
* Sentiment Analysis of Tweeter to classify Positive and Negative tweets
# Dataset that will be utilized
* From Kaggle
* [Link for the dataset](https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech)
# Methods used for data cleaning and feature engineering
## Data cleaning
* Removed contractions
* Removed stop words
* Lemmatization
* Stemming
* Removed digits,links, and non alphanumeric characters
## Feature engineering
* Converting 0 in the target variable into 'positive' and 1 into 'negative'
* Built custom pipelines for data cleaning 
* Built custom pipelines for model building
* Made the positive and negative tweets equal in length
# Model building
* Used TfidfVectorizer for text vectorizer and RandomForestClassifier as our classifier
* Cross validation of the model
* Parameter Tuning of the model with RandomizedSearchCV
* Increased the accuracy from 0.8305 to 0.8338
* Evaluate the model on the test set and with the final accuracy of 0.8706

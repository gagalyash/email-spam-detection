# sms-spam-detection

- Designed a web app that predicts if the user message is spam or not.
- Scraped the data from kaggle.
- Train different classification algorithms to get the best model.
- Deployed the machne learning model using streamlit library on heroku.

# Links and Resources Used

- Streamlit Library: https://www.streamlit.io/
- heroku Platform: https://www.heroku.com/
- Dataset Link: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
- Packages: pandas, numpy, matplotlib, seaborn, sklearn, nltk, wordcloud, pickle, streamlit

# Fetaure Engineering
We go through all the features one by one and keep adding new features. I have made the following changes and created new variables:
- Target - Rename the v1 as  column target it means if 0 : not spam and 1 : spam.
- Text - Rename the column v2 as Text.
- num_characters - Made new column to check how many number of characters are there in text.
- num_words	- Made new column to check how many number of words are there in text.
- num_sentence - Made new column to check how many number of sentence are there in text.

# Model Building

- Traditional Method
Used scikit-learn library for the Machine Learning tasks. Applied label encoding and converted the categorical variables into numerical ones.Then I splited the data into training and test sets with a test size of 20%. I tried different classification models( Logistic Regression, Random Forest Classifier, AdaBoostClassifier) and evaluated them using Mean Absolute Error.

# Model Deployment

- I have deployed the model using Streamlit library on Heroku which is a Platform As A Service(PAAS).
- web application :  https://sms-spam-detection-yg.herokuapp.com/

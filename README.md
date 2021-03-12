# About me
My name is Mauro Napoli. I'm a data science intern at Reddit, currently finishing a Master in Data Science degree at the University of San Francisco.

# churn-prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MauroDNapoli/churn-prediction/blob/main/churn_prediction.ipynb)


## Brief description
Nowadays, it is straightforward for customers to change internet or cell phone providers. That is why Telco's companies need to keep the customer engaged and prevent them from churning.
In this project, we try to predict customer churn using supervised learning algorithms in the sci-kit learn package.

## Dataset
Dataset downloaded from Kagle: https://www.kaggle.com/blastchar/telco-customer-churn

## Findings
After fitting different models with different hyperparameters combinations, we found that it is possible to predict 90% of customer churn with over 47% precision using a Gradient Boosting Classifier model.

Also, the most important features for predicting churn are:

- Contract
- TotalCharges
- Tenure
- InternetService
- OnlineSecurity

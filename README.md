# Business Analytics Project Managmenet Capstone Project

Marketing Data Analysis project for Business Analytics Project Managment course.

### Goal: Develop an ad-serving algorithm using marketing data from an online grocery store.

The project uses marketing data uploaded to Kaggle [here](https://www.kaggle.com/jackdaoud/marketing-data) by Jack Daoud. The data consists of reactions from 2,240 customers of an online grocery store to 5 different ads/promotions. Customer's reactions to the ads are recorded as 1 if the desired action is taken (acceptance) or 0 otherwise. The data set also has demographic information (age, family size, income, location) and shopping history (days since last purchase, number of purchases made with discount, amount spent in last 2 years on fruit, mean, wine, sweets).

The basic (hypothetical) problem is: suppose we are advertising online through the business shopping portal, which of the 5 ads should we show a customer to maximize the rate of acceptance?

We use the marketing data to train binary classification machine learning models that predict the probability a customer accepts each individual ad among the 5. Then we show the customer the ad that he/she is most likely to accept based on the model predictions.

We experimented with 3 different machine learning models: logistic regression, naive Bayes and random forest. In each case the models' ad recommendations **significantly outperformed the best individual ad, nearly doubling the acceptance rate** on a hold-out sample.  Among the 3 model alternatives, we found that **random forest was consistently most accurate in predicting individual ad acceptance and produced the highest acceptance rate**. 


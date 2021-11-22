# IE7374-project
# Project Goal

The increase in e-commerce usage over the past few years has created potential in the market, but the fact that the conversion rates have not increased at the same rate and how to improve the conversion rate is the problem faced by all e-commerce, which leads to the need for solutions that present customized promotions to the online shoppers. Here we use several machine learning methods to try to predetermine the classification of online consumers' purchasing intendencies.

# Data Description 

In our study, the purchasing intention is designed as a classification problem to measure the users’ intention to finalize their purchasing. Therefore, our goal is to offer the data about those who intend to purchase. In our dataset, there are ten numerical features and eight categorical features. Ten numerical features are administrative, administrative duration, informational, informational duration, product related, product related duration, bounce rate, exit rate, page value and special day. Eight categorical features are operating system, browser, region, TrafficsType, VisitorType, weekend, month and revenue. The dataset consists of feature vectors belonging to 12,330 sessions. Each session expresses each user in a one-year period to avoid any tendency to a specific campaign, special day, user profile, or period. In the dataset, 84.5% (10,422) were negative class samples that did not end with shopping, and the rest were positive class samples ending with shopping.

# Possible Solution

The goal here is to predict whether the customer would end up with shopping after visiting the e-commerce site so that we can target the customers who are most likely to end up shopping, which will increase the revenue. First, we will convert categorical variables into numerical variables, and try to normalize them all. Then we will do feature engineering to get new variables. If there exists correlation among variables, we plan to use PCA to convert variables into principal components which are not correlated. After that, we will separate our dataset into training datasets and testing datasets. K-fold Cross Validation is used to improve our models. We will apply classification models to the data set. We are interested in applying Naïve Bayes, Logistic Regression, SVM and Neural Networks classification models to our dataset. We will use confusion matrix and ROC curves to assess the performance of the model. The best model is selected based on the performance metric.

# Expected Outcome

First, we get different types of classification models, which helps us gain a deep understanding of different machine learning techniques. Second, after implementing classification tasks, we gain the knowledge of how to measure the possibility of customers choosing to shop online considering their behavior on the website. Based on the classification model, we could get to know how much these behaviors contribute to their intentions to purchase. We could offer some suggestions about how shopping stores could design their online shopping website based on the conclusions we get. 


![image](https://user-images.githubusercontent.com/92402940/142885163-1b66c6e4-3ac2-4e49-8af2-884b2a93bad8.png)

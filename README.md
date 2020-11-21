# ml_business_lab

This project is dedicated to a clothing chain in New England, which has collected data from the last-year mailing campaign. We are experts in custom relations and in clothing stores in general. Our goal is to apply machine learning and data science skills to improve the future mailing campaign.

To increase profit this year, we want to take a new dataset of potential subscribers, and predict their response using classification modelx and target only the group with high probability to respond.

We want to use the data from last-year mailing campaign to build a model which given a set of attributes will predict the class label. We first do data preprocessing by selecting key featuers, reducing cardinality, converting categorical and normalization.

We then build the model of both K Nearest Neighbour and Logistic Regression, train and test both models with cross validation and compare the accuracy of different classifiers. 

We sort the new dataset by the predicted class from Yes to No and then by probability from highest to the lowest. We can then compare customers' positive responses using the top of predicted list with the same number of randomly selected customers and visualize it with lift chart. 

Then we perform cost-benefit analysis to improve the overall profit. 
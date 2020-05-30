# Udacity-Data-Science-Capstone-Project

## Starbucks Capstone Challenge

## Table of contents:
- Python package used
- Project Motivation
- Data used
- Results
- Licensing, Authors and Acknowledgements

### Package Used:
- Numpy
- Pandas
- Matplotlib
- dattime
- sklearn
- seaborn
- jason
- math
- joblib

### Project Motivation
It is the Starbuck's Capstone Challenge of the Data Scientist Nanodegree in Udacity. We get the dataset from the program that creates the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers. We want to make a recommendation engine that recommends Starbucks which offer should be sent to a particular customer.The goal of this project is to build a model that predicts how will the customer respond will to an offer.

### Dataset Used
The data is contained in three files:

- portfolio.json - This contains offer ids and metadata about each offer (duration, type, etc.). The portfolio dataset has 10 rows which
correspond to an offer

- profile.json - This contains demographic data for each customer. The profile dataset has 17000 rows, each corresponding to a user

- transcript.json - This contains records for transactions, offers received, offers viewed, and offers completed. The transcript dataset has 306534 rows, each corresponding to an event

### Results

The baseline model accuracy and f1-score was 0.47 & 0.6 respectively
The random forest model has a better F1-score compared to logistic regression and Adaboost model.

Please find the accuracy by each model below:
- Baseline model: 047
- Logistic Classifier: 0.56
- Adaboost Classifier: 0.73
- Random Forest Classifer: 0.72

Random forest classifier has similar performance conmpared to AdaBoost classifier. AdaBoost classifer have higher chances of overfitting the training data and requires additional effort to tune. A random forest classifier is less prone to overfitting because it constructs decision trees from random training data samples. Hence we are planning to go ahead with random forest model as final model.

The top features from the feature importance of random forest models are:
Duration days, Difficulty, 2018 (the year when became a member), discount, social, web & BOGO

A summary of the results and the analysis can be found on the link mentioned here: https://medium.com/@satyam.shubham19/predicting-starbucks-customer-offer-conversion-d428bf3c1100

### Licensing, Authors and Acknowledgement

Must give credit to Stakbucks for the data



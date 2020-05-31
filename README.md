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
This post serves as final submission to the Udacity Data Science Nano Degree Program with the dataset which mimicks Starbucks rewards mobile app. We get the dataset from the program that creates the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers. The objective is to build a machine learning model that recommends Starbucks which offer should be sent to a particular customer based on their probability of conversion.

### Dataset Used
The data is contained in three files:

- portfolio.json - This contains offer ids and metadata about each offer (duration, type, etc.). The portfolio dataset has 10 rows which
correspond to an offer

- profile.json - This contains demographic data for each customer. The profile dataset has 17000 rows, each corresponding to a user

- transcript.json - This contains records for transactions, offers received, offers viewed, and offers completed. The transcript dataset has 306534 rows, each corresponding to an event

### Results

The baseline accuracy in the data is 0.47 suggesting the random chance of a customer getting an offer and responding to it is 47%.
The random forest model has a good accuracy and best F1-score on test data compared to logistic, naive and Adaboost model.

Please find the accuracy by each model below:
- Baseline model: 047
- Logistic Classifier: 0.56
- naive bayes: 0.68
- Adaboost Classifier: 0.73
- Random Forest Classifer: 0.72

We further looked into f1-score and the analysis suggests that a random forest model has the best F1-score on test data. Comparing the performance of training and test data across f1-score, precision, and recall suggests that there is no overfitting in the constructed model.

The top features from the feature importance of random forest models are:
Duration days, Difficulty, 2018 (the year when became a member), discount, social, web & BOGO

A summary of the results and the analysis can be found on the link mentioned here: https://medium.com/@satyam.shubham19/predicting-starbucks-customer-offer-conversion-d428bf3c1100

### Licensing, Authors and Acknowledgement

Must give credit to Stakbucks for the data



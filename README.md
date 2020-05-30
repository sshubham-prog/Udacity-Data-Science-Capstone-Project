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

portfolio.json - This contains offer ids and metadata about each offer (duration, type, etc.). The portfolio dataset has 10 rows which correspond to an offer and the following columns as features:
id (string) - offer id
offer_type (string) - a type of offer ie BOGO, discount, informational
difficulty (int) - the minimum required to spend to complete an offer
reward (int) - the reward is given for completing an offer
duration (int) - time for the offer to be open, in days
channels (list of strings)

profile.json - This contains demographic data for each customer. The profile dataset has 17000 rows, each corresponding to a user and the following columns as features:
age (int) - age of the customer
became_member_on (int) - the date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer-id
income (float) - customer's income

transcript.json - This contains records for transactions, offers received, offers viewed, and offers completed. The transcript dataset has 306534 rows, each corresponding to an event and the following columns as features:
event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer-id
time (int) - time in hours since the start of the test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record


# Table of Contents
1. <a href="#1.-Introduction">Introduction</a>
2. <a href="#2.-Installations">Installations</a>
3. <a href="#3.-Files">Files</a>
4. <a href="#4.-File-Descriptions">File Descriptions</a>
5. <a href="#5.-Links-and-Acknowledgements">Links and Acknowledgements</a>
6. <a href="#6.-Conclusion-and-Findings">Conclusion and Findings</a>

## 1. Introduction 
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer, and that is the challenge to solve with this data set.

**In this project, customer demographics and transactional records are analyzed to predict whether a customer is likely to accept a certain offer or reject it.**



## 2. Installations 
The following modules have been used in the work done in this Project.
1. **Pandas and Numpy:** Modules used for data manipulation.
2. **Sklearn:** For Data Processing and Modelling.
3. **XGBoost:** For Classification
4. Other libraries used are generally found built in in Anaconda.

## 3. Files 
The repository consists of a total of 4 Files.
1. This **Readme** file.
2. The python file **Starbucks_Capstone_Udacity**. This is the main file that loads the datasets provided in this project, performs preprocessing and modelling.
3. **portfolio.json** - containing offer ids and meta data about each offer (duration, type, etc.)
4. **profile.json** - demographic data for each customer
5. **transcript.json** - records for transactions, offers received, offers viewed, and offers completed


## 3. File Descriptions

Here is the schema and explanation of each variable in the files:

**1. portfolio.json**

- id (string) - offer id
- offer_type (string) - type of offer ie BOGO, discount, informational
- difficulty (int) - minimum required spend to complete an offer
- reward (int) - reward given for completing an offer
- duration (int) - time for offer to be open, in days
- channels (list of strings)

**2. profile.json**

- age (int) - age of the customer
- became_member_on (int) - date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income

**3. transcript.json**

- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since start of test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record

## 5. Links and Acknowledgements 
1. [Udacity](https://www.udacity.com/): This project is part of the data science nano degree I am doing in collaboration with Udacity.
2. [Starbucks](https://www.starbucks.com/): The company providing the pre-labeled dataset for the analysis.


## 6. Conclusion and Findings 
The results of the anaylsis and conclusions can be found in the following article. [Muneeb Aizaz Starbucks Capstone Project](https://muneeb-aizaz23.medium.com/predicting-customer-response-to-different-offer-types-starbucks-capstone-challenge-ae2815a18b5d)


```python

```

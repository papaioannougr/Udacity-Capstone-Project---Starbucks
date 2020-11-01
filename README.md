# Udacity-Capstone-Project---Starbucks

This repository contains all the necessary data and code files related with the  Capstone final project of the Udacity - DataScience nanodegree part.

## Description:
This project was as a requirement for the Udacity Data Scientist Nanodegree. The purpose of the project is by using the available transactional, customer and offer data
to provide an analysis to Starbucks about recomendation that can be done in order to optimize the offerr process.
Data provided during the project were obtained by asimulation of Starbucks mobile application in which customers, receive and view offers made to themwhile they can pay their drinks in the stores.

## Analysis:
The analysis is consisted of 3 parts:

1. Data processing. In this step all data read and processed, applying cleansing actions. For portfolio and profile dataframes there were some changes in column names, Especially in profile dataframe, missing values were identified for column:age and a null value was applied. Information in trascript dataframe was aggregated in a list of meaningful columns which includes all the available information

2. Exploratory Analysis. A thorough investigation took place in order to identify key features that affect the positive respond to an offer. Along with available demografic information analyzed and useful conclusion extracted about the profile of customers

3. Modelling. The purpose in this step of the analysis, wasto build a model that can be used by Strabacks, in order to identify more effectively customers that will respond to the offer. I used Grid Search, in order to select the best classification model for the avbailable data. The best model was the random Forest classifier which accomplishes accuracy of 79% on the test data.


## Contents:

1. Data folder: It contains the data for the analysis:

  - portfolio.json: infromation for the offers
  
  - profile.json  : demographics of the customers
  
  - transcript.rar: detailed information about actions taken for the offers. This dataset was compressed due to its large size.
  
2. Starbucks_Capstone_notebook.ipynb: It's the jupyter notebook where all analysis took place. 

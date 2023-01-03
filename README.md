# Fetal-Health-Classification
Classify the health of a fetus as Normal, Suspect or Pathological using CTG data

## Background: 
Reduction of child mortality is reflected in several of the United Nations' Sustainable Development Goals and is a key indicator of human progress. Cardiotocograms (CTGs) are a simple and cost accessible option to assess fetal health, allowing healthcare professionals to take action in order to prevent child and maternal mortality. 

## Data: 
This dataset contains 2126 records of features extracted from Cardiotocogram exams, which were then classified by three expert obstetritians into 3 classes: Normal, Suspect and Pathological.


## Problem: 
classify the health of a fetus as normal(label: 0), suspect(label:1), pathological(label:2) using CTG data

## Step of this project:
1. Examine the dataset to get an overall understanding of the data
2. Impute missing data if any exists
3. Train different classification models and get the higheste accuary score
    -  Tained Models: knn, random forest tree, XGB classifier, support vector machine, GussianNB 
    -  Gridsearch to get the best paramters
    -  Explore feature importantce by training a classification model
    -  Retrain the model to check for accuary based on feature importance
4. Select the best performance model
5. predict the test set using selected model¶

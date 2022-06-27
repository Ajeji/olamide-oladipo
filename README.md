
# SOUTH AFRICAN LANGUAGE IDENTIFICATION HACK 2022


In this this project,a classifier model was built to take text which is in any of South Africa's 11 Official languages and
Identify which language the text is in. 
## Objective
The objective of this project is to determine the natural language that a piece of text is written in.

## Roadmap

- Importing Packages
- Loading Data
- Exploratory Data Analysis(EDA)
- Modelling
- Kaggle Sample Submission
- Conclusion
- Refrences




## Usage/Examples

- Libraries for importing and loading data

       e.g import pandas as pd
- Libraries for data preparation
                                             
      e.g import re

- Libraries for data visualizations

      e.g import seaborn as sns
- Libraries for assessing model accuracy

       e.g from sklearn.metrics import classification_report, confusion_matrix, f1_score, precision_score, recall_score

- Libraries for building classification models

      e.g from sklearn.pipeline import Pipeline
## The DATAset
To run this project, you will need to download the *train* and *test* dataset 

https://www.kaggle.com/competitions/south-african-language-identification-hack-2022/data?select=train_set.csv

https://www.kaggle.com/competitions/south-african-language-identification-hack-2022/data?select=test_set.csv


## Variables
- Dependent   variable   - "lang_id"
- Independent variable   - "text"
## Classifier
- Naive bayes classfier was used in Model building

        Naive Bayes model is easy to build and particularly useful for very large data sets.    
## Evaluation
- Confusion matrix
- Accuracy score
- Classification report
## Conclusion
This project covers techniques for cleaning text data and extracting features to use with machine learning models. It also demonstrated how TfidVectorizer can be used to clean text data and extract features, transforming the text data into a matrix of numbers that can be fed into a machine learning model.Results of the accuracy was made to Kaggle and saved as well for future use.
## Refrences
https://readme.so/editor
https://www.youtube.com/watch?v=4ATucrptdYA

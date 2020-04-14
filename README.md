# Predicting User Churn from a Music Streaming Platform

## Installation

Libaries used in this project are as follows:
- pandas
- matplotlib.pyplot
- seaborn
- datetime
- pyspark.sql -  SparkSession, Window
- pyspark.sql - functions
- pyspark.sql.functions - udf, countDistinct, split, count, when, sum as ssum, col, last, lit, concat, avg, desc
- pyspark.ml - feature - StringIndexer, VectorAssembler, StandardScaler
- pyspark.ml - classification - LogisticRegression, RandomForestClassifier
- pyspark.ml - Pipeline
- pyspark.ml - evaluation - MulticlassClassificationEvaluator
- pyspark.ml - tuning - CrossValidator, ParamGridBuilder

## Project Overview
Sparkify is a music streaming platform data-set provided by Udacity in the data science for enterprise Nanodegree program. Within this platform, the users have the option to subscribe to the service as either a paid user, or a free user (including advertisements). As part if this project I have used this data-set to explore, identify and predict customer churn (when a customer cancels their subscription) based on particular features derived from the data. I have approached this 

The aim of this project is to develop machine-learning models to help Sparkify predict a particular customer who is likely to churn. This could be used to support additional marketing activities or promotional offers to help retain these customers.

## Data
The data analysed within this notebook is provided by Udacity as 'mini_sparkify_event_data.json'.

## Results
Results can be found either in the .ipynb file in this repository or in the following Medium post - https://medium.com/@hinton_/predicting-user-churn-from-a-music-streaming-platform-9c82424c04d7

# Sparkify Udacity Capstone Project

## Overview and motivation
This project is part of the Udacity Data Scientist Nanodegree. Here we will analyse a small subset of a 12GB dataset using the spark framework. 
The dataset contains events from a music streaming app called "Sparkify" whose users either use the service through the free tier or the paid tier.
The notebook contains the code needed to clean, analyse, prepare, train and test various models and select the best one to predict customer churn.

## Installation
Following packages will be required to run this in an environment
  - pyspark
  - jupyter
  - seaborn
  - pandas
  - datetime
  - matplotlib
  - numpy
  
## Files
  - Sparkify.ipynb: This is the main file containing all the code for the project.
  
## Results & Summary
The test data is relatively small with 225 users from which 52 have churned. We create some basic features like number of songs and artists heard, 
number of unique pages visited etc... Please visit my blog post for more details.<>

Using 3 classifcation models: Logistic Rregression, Random Forest and Gradient Boosted Trees (GBT) with default params we find that the GBT gives us the best f1
score of 0.83. We user hyper parameter tuning to improve the the scores ending with an f1 score of <>

## References
The project was made possible due to an entire communicty of data scientists solving similar problems and a lot of preparation material provided by udacity.
Other key sources that influenced my approach are:
  - [Spark documentation](https://spark.apache.org/docs/latest/index.html)
  - [Ok-Udacity](https://github.com/ok-udacity/sparkify/blob/master/Sparkify.ipynb)



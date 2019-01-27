# Evaluation-of-machine-learning-algorithms-on-walmart-stock-price-data
CSCI 54900 INTELLIGENT SYSTEMS PROJECT

## Description

* Item Implemented Min-Max Normalization on Walmart data – scaled the data to fixed range
* Item Feature selection is implemented to get weighed variables using Recursive Feature Elimination (RFE)
* Item Recursive Neural Networks (RNN), AutoRegressive Integrated Moving Average (ARIMA) and Support Vector Machines (SVM) Machine learning algorithms are used to build predictive models respectively.
* Item In performance analysis, Confusion matrix and root mean squared error (RSME) is used to evaluate prediction models.
* Item Among all the algorithms used ARIMA shows least error rate.

## Dataset

**sample walmart dataset**

<img src="https://github.com/Premchand95/Evaluation-of-machine-learning-algorithms-on-walmart-stock-price-data/blob/master/reports%20%26%20results/img/Picture1.png" height="250" width="250">


## Feature Selection

**We got "High", "Low" , "Open" as top features using Recursive Feature Elimination (RFE)**

<img src="https://github.com/Premchand95/Evaluation-of-machine-learning-algorithms-on-walmart-stock-price-data/blob/master/reports%20%26%20results/img/Picture2.png" height="350" width="450">

## Dividing dataset into training and testing

**80% data is for training & 20% data is for testing**

<img src="https://github.com/Premchand95/Evaluation-of-machine-learning-algorithms-on-walmart-stock-price-data/blob/master/reports%20%26%20results/img/trainAndtest.png" height="120" width="350">

## Recurrent Neural Networks

**Used Elman Network together with LSTM in RNN**

<img src="https://github.com/Premchand95/Evaluation-of-machine-learning-algorithms-on-walmart-stock-price-data/blob/master/reports%20%26%20results/img/Picture3.png" height="120" width="350">

## ARIMA

**Actual vs Forecasted series**

<img src="https://github.com/Premchand95/Evaluation-of-machine-learning-algorithms-on-walmart-stock-price-data/blob/master/reports%20%26%20results/img/Picture6.png">

## Results

**ARIMA got less error rate than other alogorithms

Predictive Model | RNN | ARIMA | SVM
------------ | ------------- | ------------- | -------------
RSME | 0.0179 | 0.00885 | 1.6306

 **Forecast of walmart data for next 5 days using ARIMA**
 
<img src="https://github.com/Premchand95/Evaluation-of-machine-learning-algorithms-on-walmart-stock-price-data/blob/master/reports%20%26%20results/img/Picture10.png" height="250" width="250">



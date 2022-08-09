# Module-12-Challenge---Cassification-Problem

## Overview of the Analysis

Credit risk poses a classification problem that’s inherently imbalanced. The reason is that healthy loans easily outnumber risky loans. For this Challenge, you’ll use various techniques to train and evaluate models with imbalanced classes. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Instructions

* The instructions for this Challenge are divided into the following subsections:

* Split the Data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Predict a Logistic Regression Model with Resampled Training Data

* Write a Credit Risk Analysis Report

## Results


* Machine Learning Model 1:

  * The model is likely to perform well as the accuracy is high to 95%. For "0" healthy loan, the precision is 100% and recall is 99%. For "1" high-risk loan, the precision declined to 85% and 91% recall. 

* Machine Learning Model 2:

  * Afer oversampled the data, we can see the accuracy improved from 95% to 99%. The model is still performing well on predictiong "0" healthy loan at 100% precision and 99% recall. For "1" high-risk loan, precision declined a little bit to 84% but recall increased from 91% to 99%. That means the sensitivity is higher and true positive rate is higher and false negative rate is lower.


## Summary

From the comparision of the two models, I would recommend the Machine Learning Model 2 which includes Random Oversampling. The overall accuracy is improved with this model but most importantly, the recall relating to high-risk loans is improved from 91% to 99%. That means, it can help to reduce the risk of default the high-risk loans when it was categorized as the healthy loans.
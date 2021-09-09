# COMP90051 Statistical Machine Learning - Project 1 

This is project 1 of COMP90051 Statistical Machine Learning course at the University of Melbourne.

## Group Members
#### Group Name: Hunter
- Xiaoyu Wu 1218098
- Haohan Zhou 958579

## Overview
The primary problem of this project is to identify human action recognition by classifying the behaviour based on a sample of 3D joints movements sequences. In addition, the distribution of behaviour categories is highly skewed in the given data, this leads to another problem --- imbalanced data classification. In this project, we implement classical machine learning and neural network methods to address these problems. The proposed models will be compared and evaluated regarding the overall performance of the Kaggle competition and the Accuracy(ACC) score. 

## Directories & Files
* `data/` 
> jupter notebooks for modelling of LR, RF, SVM, XGBoost, CNN, LSTM
* ` Group10_Final_Report.pdf` 
> Final project report of this project
* `supporting_evidence`
> - Meeting Minutes
> - Study Notes for imbalanced data classfication
> - Parameter Tuning Records
> - Reference Links

## Data
The given training data contains 9388 sequences of 3D joint movements with 960 features, which belong to 49 classes. For validating the model, we randomly split 20% data from the given training dataset as the validation set and the rest of the data will be used for training models. Another test data with 2859 sequences will be used for generating the final classification and evaluation.

## Approaches
Logistic Regression, Random Forest, SVM, XGboost, CNN and LSTM are used to categorize human behaviour from 3D joints movement sequences and handle the data imbalance.
* `` 


For detailed information, please refer to the project report. Thank you!

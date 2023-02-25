# Credit_Risk_Analysis

## Overview
The purpose of this challenge was to try different sampling methods on a credit card dataset. Secondly two models will be tested that reduce bias to predict credit card risk.

## Results

Naive Random Oversampling

* Accuracy: 67.3%
* Precision: 99%
* Recall: 60%

![1](https://github.com/michaeltzhou/Credit_Risk_Analysis/blob/main/Resources/randomoversampler.PNG)

SMOTE Oversampling

* Accuracy: 66.2%
* Precision: 99%
* Recall: 69%

![2](https://github.com/michaeltzhou/Credit_Risk_Analysis/blob/main/Resources/smoteover.PNG)

Undersampling

* Accuracy: 66.3%
* Precision: 99%
* Recall: 40%

![3](https://github.com/michaeltzhou/Credit_Risk_Analysis/blob/main/Resources/clusterunder.PNG)

Combination Sampling

* Accuracy: 54.5%
* Precision: 99%
* Recall: 57%

![4](https://github.com/michaeltzhou/Credit_Risk_Analysis/blob/main/Resources/smoteennoverunder.PNG)

Balanced Random Forest

* Accuracy: 78.8%
* Precision: 99%
* Recall: 91%

![5](https://github.com/michaeltzhou/Credit_Risk_Analysis/blob/main/Resources/balancedrandomforest.PNG)

Easy Ensemble

* Accuracy: 92.5%
* Precision: 99%
* Recall: 94%

![6](https://github.com/michaeltzhou/Credit_Risk_Analysis/blob/main/Resources/easyensemble.PNG)

It would appear that EasyEnsembleClassifier is the best suited towards the dataset, as it has the highest accuracy score of 92.5%.

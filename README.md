# Credit_Risk_Analysis

## Overview of the analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We employed different techniques to train and evalutate models with unbalanced classes. We used imbalanced-learn and scikit-learn libraries to build and evalutate models using resampling.

## Results
Naive RandomOverSampling
    - Oversample the data using the RandomOverSampler algorithm.

![Naive Random Oversampliing](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling.png)


SMOTE
    - Oversample the data using the SMOTE algorithm.

![SMOTE Oversampling](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling.png)

ClusterCentroids
    - Undersample the data using the ClusterCentroids algorithm.

![ClusterCentroids](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)

SMOTEENN
    - Combinatorial approach of over- and undersampling using the SMOTEENN algorithm.

![SMOTEENN](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)

### Compare two machine learning models that reduce bias, to predict credit risk.
BalancedRandomForestClassifier
    
![BalancedRandomForestClassifier](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier.png)

EasyEnsembleAdaBoostClassifier

![EasyEnsembleAdaBoostClassifier](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleAdaBoostClassifier.png)



## Summary

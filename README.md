# Credit_Risk_Analysis

## Overview of the analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We employed different techniques to train and evalutate models with unbalanced classes. We used imbalanced-learn and scikit-learn libraries to build and evalutate models using resampling.

## Results
Naive RandomOverSampling
    - Oversample the data using the RandomOverSampler algorithm.

![Naive Random Oversampliing](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling_comb.png)


SMOTE
    - Oversample the data using the SMOTE algorithm.

![SMOTE Oversampling](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling_comb.png)

ClusterCentroids
    - Undersample the data using the ClusterCentroids algorithm.

![ClusterCentroids](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids_comb.png)

SMOTEENN
    - Combinatorial approach of over- and undersampling using the SMOTEENN algorithm.

![SMOTEENN](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN_comb.png)

### Compare two machine learning models that reduce bias, to predict credit risk.
BalancedRandomForestClassifier
    
![BalancedRandomForestClassifier](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier_comb.png)

EasyEnsembleAdaBoostClassifier

![EasyEnsembleAdaBoostClassifier](https://github.com/pcar22/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier_comb.png)



## Summary
In the first four models we undersampled, oversampled and did a combination of both to try and determine which model is best at predicting credit risk. In the next two models, we resampled the data to try and determine a better model.

Typically in your models you want a good balance of recall and precision and based on these results, I would recommend the EasyEnsembleAdaBoostClassifier model.
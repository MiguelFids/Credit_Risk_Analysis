# Module 18 Challenge
### Miguel Fidelino

## Overview of the analysis
Using imbalanced-learn and scikit-learn libraries, we are to build and evaluate models to predict credit rating using resampling: oversalmple using RandomOverSampler and SMOTE, undersample using ClusterCentroids, and using a combination of the two latter samplers using SMOTEENN. 

## Results

Below are the balanced accuracy score and the precision and recall scores of all six machine learning models

* Random Over Sampler

![RandomOverSampler](img/RandomOverSampling.png)

* Snthetic Minority Over Sampling Technique (SMOTE)

![SMOTE](img/SMOTE.png)

* ClusterCentroids

![ClusterCentroids](img/ClusterCentroids.png)

* SMOTE + Edited Nearest Neighbours (SMOTEENN)

![SMOTEENN](img/SMOTEENN.png)

* Balanced Random Forest Classifier

![BalancedRandomForestClassifier](img/BalancedRandomForestClassifier.png)

* Easy Ensemble Classifier

![EasyEnsembleClassifier](img/EEC.png)

## Summary

The Easy Ensemble Classifier is perhaps the best model to use, as it provides the highest possible f1 summary score. Most importantly, the Easy Ensemble Classifier can detect high risk scores relatively better than the rest of the models produced.

However, I would not use any of these classifiers as the precision is very poor, with Easy Ensemble Classifier being the highest with 7% precision, and 90% recall.
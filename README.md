# Credit_Risk_Analysis #

## Overview ##
	Jill wanted a more in-depth look into machine learning and predicting outcomes for low or high-risk customers. In this exercise we used a variety of model to show jill the various outcomes.

## Results ##
	We perform 6 different predictive models with various outcomes and accuracy thresholds. So below:
 
-RandomOverSampler >> Balanced Accuracy Score=61% & Recall Score= High (.58); Low (.63)
-SMOTE>> Balanced Accuracy Score=64% & Recall Score= High (.60); Low (.67)
-ClusterCentroids>> Balanced Accuracy Score=55% & Recall Score= High (.64); Low (.46)
-SMOTEENN>> Balanced Accuracy Score=68% & Recall Score= High (.81); Low (.55)
-BalanceRandomForestClassifier>> Balanced Accuracy Score=70% & Recall Score= High (.59); Low (.80)
-EasyensembleClassifier>> Balanced Accuracy Score=70% & Recall Score= High (.59); Low (.80)

## Summary ##
	I would recommend the only Model that had the highest Accuracy Score which would be BalanceRandomForestClassifier & EasyensembleClassifier with a 70%. 

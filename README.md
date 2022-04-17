# Credit_Risk_Analysis

## Overview of the analysis: 

The purpose of this analysis was to use different algorithms to predict credit risk, and evaluate which one works best to predict credit risks. 

## Results: 

As shows on the images below, you will see the best results were from the EasyEnsembleClassifier algorithm with a f1 score of 0.97 and a balanced accuracy score of 0.92. The worst results were from the ClusterCentroids with a f1 score of 0.60 and a balance accuracy score of 0.63.

I will list all six machine learning modules from best to worst below:

-	EasyEnsembleClassifier: Balance Accuracy Score: 0.92 / f1 score: 0.97. 

![EasyEnsembleClassifier](https://user-images.githubusercontent.com/92958939/163700357-7302fb7e-e057-4292-be1d-3b43d140b2ec.png)

-	BalanceRandomForestClassifier: Balance Accuracy Score: 0.78 / f1 score: 0.95. 

![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/92958939/163700361-2f7d502d-7a95-4e87-ba7d-f8a1f430e5f7.png)

-	LogisticRegression: Balance Accuracy Score: 0.63 / f1 score: 0.79. 

![LogisticRegression](https://user-images.githubusercontent.com/92958939/163700365-c67ba985-3fd3-4309-95a7-573d0a2199d0.png)

-	SMOTE: Balance Accuracy Score: 0.63 / f1 score: 0.78. 

![SMOTE](https://user-images.githubusercontent.com/92958939/163700372-5221e448-dca1-41f4-bd7c-25af91b4d7a5.png)

-	SMOTEENN: Balance Accuracy Score: 0.51 / f1 score: 0.74. 

![SMOTEENN](https://user-images.githubusercontent.com/92958939/163700378-a7303af1-8fe6-4228-ad4d-cc185c5ebfa9.png)

-	ClusterCentroids: Balance Accuracy Score: 0.63 / f1 score: 0.60.

![ClusterCentroids](https://user-images.githubusercontent.com/92958939/163700382-310bed0a-1bd6-494e-a520-ae028b7afe34.png)

## Summary: 

The best results were from the EasyEnsembleClassifier due to the scores being closest to 1. Meaning that the predictions are more accurate when the precision, recall, f1, and the Balance Accuracy Score is closest to 1.

I would recommend using the EasyEnsembleClassifier module due to its higher chance of providing a more accurate prediction. 


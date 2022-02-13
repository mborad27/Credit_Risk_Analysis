# Credit Risk Analysis: Machine Learning
## Overview
LendingClub is a peer to peer lending service company that wants to use machine learning to predict credit risk. Upper management believes that this will provide a quicker and more reliable loan experience. In addition, they surmise that machine learning will lead to a more accurate identification of good candidates of loans for which will lead to lower default rates. Credit risk is an unbalanced classification problem, as good loans outnumber risky loans. We will employ different techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub, we will build and evaluate models using resampling.
## Results
The results for all six machine learning algorithms are shown below with their outputs supported with images:
| ML Model | Balanced Accuracy Score | Precision | Recall | F1 |
| --- | ----------- | -------- | -------- | ------- |
| Naive Random Oversampling | 0.68 | 0.99 | 0.68 | 0.80 |
| SMOTE Oversampling | 0.66 | 0.99 | 0.66 | 0.79 |
| Cluster Centroid Undersampling | 0.43 | 0.99 | 0.44 | 0.60 |
| SMOTEENN Combination Sampling | 0.57 | 0.99 | 0.57 |0.72 |
| Balanced Random Forest Classifier |0.90| 0.99| 0.91 | 0.95|
| Easy Ensemble AdaBoost Classifier | 0.94| 0.99 | 0.94 | 0.97|
* Naive Random Oversampling:
![naive 1](https://user-images.githubusercontent.com/92230478/153733975-98009b95-6fa4-4f78-8fb4-f57f2d3e45f5.PNG)
![haive 2](https://user-images.githubusercontent.com/92230478/153733977-68283c57-4d2e-4bcc-bb41-4db49544ed0d.PNG)
* SMOTE Oversampling:
![smote 1](https://user-images.githubusercontent.com/92230478/153734009-14893c1a-dcdb-4c9e-9828-79501c0d28a8.PNG)
![smote 2](https://user-images.githubusercontent.com/92230478/153734011-d59a6ada-1115-48dc-a788-f6c06a89e3fc.PNG)
* Cluster Centroid Undersampling:
![cluster centrod](https://user-images.githubusercontent.com/92230478/153734053-c75608c7-7118-4848-9bc7-cf1f6368e6c0.PNG)
* SMOTEEN Combination Sampling:
![smoteeen](https://user-images.githubusercontent.com/92230478/153734072-850289fe-8dfd-4f6d-b60a-b6c57998a9d5.PNG)
* Balanced Random Forest Classifier:
![balanced random](https://user-images.githubusercontent.com/92230478/153734108-5b9d08a4-f9d7-4368-9bd8-779063b5aa83.PNG)
* Easy Ensemble AdaBoost Classifier:
![Easy Ensemble](https://user-images.githubusercontent.com/92230478/153734113-d8eab828-cfcc-4949-8819-29de1651fc72.PNG)

## Summary
In reviewing all six models, the Easy Ensemble Adaboost Classifer model yielded the best results with an accuracy rate of 94% and a 7% precision rate when predicting "High Risk candidates. The sensitivity rate (recall) was also the highest at 94% compared to the other models. The result for predicting "Low Risk" was also the highest with the sensitivity rate at 94% and an F1 score of 97%. This model is the best choice to use for this type of analysis due to its high accuracy, precision, and sensitivity.

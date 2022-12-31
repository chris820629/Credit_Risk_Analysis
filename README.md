# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, using several sampling methods to evaluate the most accurate sampling strategy. Then two new machine learning models to assess the accuracy of predicting credit risk. 
## Results
Low Risk Scores
Naive Random Oversampling: 1.00 (Precision score), 0.64 (Recall score)
Cluster Centeroid Undersampling: 1.00 (Precision score), 0.40 (Recall score)
Combo Sampling: 1.00 (Precision score), 0.57 (Recall score)
SMOTE Oversampling: 1.00 (Precision score), 0.68 (Recall score)
Random Forest: 1.00 (Precision score), 1.00 (Recall score)
Easy Ensemble: 1.00 (Precision score), 0.95 (Recall score)
## Summary
Based on the prediction results from various results, it can be concluded that overall both precision and recall values the low risk prediciton are higher than the predictino of high risk analysis. In addition, I believev false positive (precision) is more critical than false negativev (recall) for bank operation profitibility. 
Using this convention, SMOTE ovevrsampling produces the best oversample data. On the machine learning model aspect, the Random forest model out perform the Easy ensemble in recall score since both models were able to successfully predict the false positivev (precision score). In summary, I would recommend the random forest model for this particular credit risk analysis.

Naive Random Oversampling
![Naive_Random_Oversampling.png](https://github.com/chris820629/Credit_Risk_Analysis/blob/main/Images/Naive_Random_Oversampling.png)
Cluster Centeroid Undersampling
![Cluster_Centeroid_Undersampling.png](https://github.com/chris820629/Credit_Risk_Analysis/blob/main/Images/Cluster_Centeroid_Undersampling.png)
Combo Sampling
![Combo_Sampling.png](https://github.com/chris820629/Credit_Risk_Analysis/blob/main/Images/Combo_Sampling.png)
SMOTE Oversampling
![SMOTE_Oversampling.png](https://github.com/chris820629/Credit_Risk_Analysis/blob/main/Images/SMOTE_Oversampling.png)
Random Forest
![Random_Forest.png](https://github.com/chris820629/Credit_Risk_Analysis/blob/main/Images/Random_Forest.png)
Easy Ensemble
![Easy_Ensemble.png](https://github.com/chris820629/Credit_Risk_Analysis/blob/main/Images/Easy_Ensemble.png)

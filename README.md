# Credit_Risk_Analysis

## Overview of the analysis  
  For this challenge we performed six different machine learning models, with the objective of finding out with model performs better and if we can recommend on particular machine learning model.  
  To evaluate the models, we will be using the credit card credit dataset from Lending Club. The machine learning models we will be using are:  
-	Oversampling
-	SMOTE Oversampling
-	Undersampling
-	Combination (Over and Under) Sampling
-	Balanced Random Forest Classifier
-	Easy Ensemble AdaBoost Classifier

## Results  

The results of all 6 machine learning models are summarized in the table below, the screenshots to support these results are under the table

#### Models Results Table
| Machine Learning Model| Balanced Accuracy Score |Precision | Recall|
| ------------- |-------------|-------------|-------------|
| Oversampling                     | 0.66 | 0.99| 0.67 |
| SMOTE Oversampling               | 0.63 | 0.99| 0.64 |
| Undersampling                    | 0.51 | 0.99| 0.44 |
| Combination Sampling             | 0.63 | 0.99| 0.57 |
| Balanced Random Forest Classifier| 0.78 | 0.99| 0.91|
| Easy Ensemble AdaBoost Classifier| 0.93 | 0.99| 0.94|


#### Image 1 – Oversampling Results  
![](images/oversampling_results.jpg)  
#### Image 2 – SMOTE Oversampling Results  
![](images/smote_oversampling_results.jpg)  
#### Image 3 – Undersampling Results  
![](images/undersampling_results.jpg)  
#### Image 4 – Combination Sampling Results  
![](images/combination_results.jpg)  
#### Image 5 – Balanced Random Forest Classifier Results
![](images/br_forest_classifier_results.jpg)  
#### Image 6 – Easy Ensemble AdaBoost Classifier Results  
![](images/easy_ensemble_AC_results.jpg)  


## Summary  

The resampling models of machine learning (Oversampling, SMOTE Oversampling, Undersampling and Combination), all provide balance accuracy scores and recall scores that are not particularly good, signifying that this method could approve high number of loans that are high risk of default. Therefor the resampling models do not seem ideal for this case.  
The ensemble models (Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier), both provide higher balance accuracy than the resampling models, but the Easy Ensemble AdaBoost Classifier have a significant higher Balanced Accuracy and Recall (sensitivity) scores, of 93% and 94% respectively.   

With the results the best machine learning model for the credit risk analysis is Easy Ensemble AdaBoost Classifier.


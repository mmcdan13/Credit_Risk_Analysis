# Credit_Risk_Analysis
Supervised Learning


## Overview of the Loan Prediction Risk Analysis


### Purpose 

The purpose of this analysis is to assist FastLending, a peer-to-peer lending services company, in predicting credit risk in order to provide a quicker and more reliable loan experience. Machine learning will lead to a more accurate identification of good candidates for loans which should lead to lower default rates. 

### Results

I created and trained six machine learning models to predict credit risk of loan candidates. These six machine learning models take into consideration the imbalance of classes (most loans are good loans and are not risky) and addresses the imbalance with a resampling technique. Below is a bulleted list that describes the balanced accuracy score, and the precision and recall scores of each model: 

* Naive Random Oversampler
       * Balanced Accuracy Score: 0.5854457252150106
       * Precision: 0.01 for high_risk / 1.00 for low_risk 
       * Recall: 0.53 for high_risk / 0.64 for low_risk
* SMOTE Oversampling
       * Balanced Accuracy Score: 0.6054959236740347
       * Precision: 0.01 for high_risk / 1.00 for low_risk 
       * Recall: 0.53 for high_risk / 0.68 for low_risk
* Cluster Centroids Resampling
       * Balanced Accuracy Score: 0.48692425294010405
       * Precision: 0.00 for high_risk / 1.00 for low_risk 
       * Recall: 0.48 for high_risk / 0.49 for low_risk
* SMOTEENN
       * Balanced Accuracy Score: 0.6550019350154641
       * Precision: 0.01 for high_risk / 1.00 for low_risk 
       * Recall: 0.74 for high_risk / 0.57 for low_risk
* Balanced Random Forest Classifier
       * Balanced Accuracy Score: 0.8834641092705608
       * Precision: 0.03 for high_risk / 1.00 for low_risk 
       * Recall: 0.77 for high_risk / 0.88 for low_risk
* Ensemble AdaBoost Classifier 
       * Balanced Accuracy Score: 0.9276176281507968
       * Precision: 0.06 for high_risk / 1.00 for low_risk 
       * Recall: 0.92 for high_risk / 0.94 for low_risk


### Summary

To evaluate a model's performance, I looked at three metrics: accuracy, precision, and recall. Accuracy measures how often the model correctly classifies the data. Recall measures how likely the model is to classify a true positive correctly. Precision measures how likely it is that the outcome of the model is actually true. In considering these three metrics, I would recommend using the Ensemble AdaBoost Classifier. It has the highest accuracy score, and the highest recall score of all the models. 
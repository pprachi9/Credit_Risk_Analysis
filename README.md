# Credit_Risk_Analysis

## Overview of the Analysis 

It is very tough to predict credict risk. For this project, we can analyze how all the factors in loan_stats csv help predict whether someone is at high or low risk status. In this project, we will be analyzing this by developing a supervised machine learning models that could effectively predict credit risks. We used the following algorithms were used:
- Naive Random Oversampling using RandomOversampler
- SMOTE Oversampling
- Undersampling using Cluster Centroid
- Combination (Over and Under) Sampling using SMOTEENN
- Balanced Random Forest Classifying
- Easy Ensemble Classifying

We split the data into training and testing datasets for each of the algorithms and accuracy scores, confusion matrixes, and classication reports were cretaed as results. 

## Results

### Naive Random Oversampling results:  
<img width="726" alt="Screen Shot 2022-04-27 at 3 52 50 PM" src="https://user-images.githubusercontent.com/93291994/165620174-d438aa5a-5b2f-4b37-a1dd-308ca9acc304.png">
-Accuracy Score: 65%
-Precision High Risk: 1%
-Precision Low Risk: 100%
-Recall High Risk: 68%
-Recall Low Risk: 68%

### SMOTE oversampling results: 
<img width="713" alt="Screen Shot 2022-04-27 at 3 54 18 PM" src="https://user-images.githubusercontent.com/93291994/165620401-03b47cec-611c-4fca-8acf-cc6e137f72a8.png">
-Accuracy Score: 63%
-Precision High Risk: 1%
-Precision Low Risk: 100%
-Recall High Risk: 59%
-Recall Low Risk: 66%

### Undersampling results: 
<img width="709" alt="Screen Shot 2022-04-27 at 3 55 35 PM" src="https://user-images.githubusercontent.com/93291994/165620588-1a98ec01-b15a-4ebe-9958-47e0e6d18f49.png">
-Accuracy Score: 52%
-Precision High Risk: 1%
-Precision Low Risk: 100%
-Recall High Risk: 60%
-Recall Low Risk: 43%

### Combination(over and undersampling) results:
<img width="746" alt="Screen Shot 2022-04-27 at 3 56 37 PM" src="https://user-images.githubusercontent.com/93291994/165620754-12c0534d-4461-444f-921e-2538dbcd7ba0.png">
-Accuracy Score: 62%
-Precision High Risk: 1%
-Precision Low Risk: 100%
-Recall High Risk: 71%
-Recall Low Risk: 53%

### Balanced Random Forest Classifier results: 
<img width="701" alt="Screen Shot 2022-04-27 at 4 02 24 PM" src="https://user-images.githubusercontent.com/93291994/165621634-2105591b-1bb0-4b2e-b09a-cb1126136d17.png">
-Accuracy Score: 79%
-Precision High Risk: 4%
-Precision Low Risk: 100%
-Recall High Risk: 67%
-Recall Low Risk: 91%

### Easy Ensemble Classifying results:
<img width="716" alt="Screen Shot 2022-04-27 at 4 03 52 PM" src="https://user-images.githubusercontent.com/93291994/165621872-384c92e3-37e2-4857-8ee0-8ce75055cc82.png">
-Accuracy Score: 93%
-Precision High Risk: 7%
-Precision Low Risk: 100%
-Recall High Risk: 91%
-Recall Low Risk: 94%

## Summary 

After running all of the credit risk algorithms, we found that they have low precision in evaluating whether a credit card risk is high. Significant results were shown by the Ensemble algorithm, especially in the sensitivity of high-risks credits and can disclose almost all high-risk credit with a recall of 91%. In contrast, due to low precision, a lot of low-risk credits are being misinterpreted as high-risk, jeopardizing the bank's credit scheme and making it pass up income prospects.  In conclusion, I would inform the bank against using any of these algorithms to expect credit risk.




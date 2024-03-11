# Credit Risk Classification

## Overview
The purpose of this analysis is to review how accurate our data model is at predicting the creditworthiness of borrowers of peer-to-peer lending services. 

## Results
Below are some of the findings I have found from my analysis:
- F1-Score for borrowers 0 (Healthy Loans) = 100%, F1-Score for borrowers 1 (High Risk Loans) = 88%. Normally getting an accuarcy of 100% in something would be amazing but in this instance however this is not the case. The 100% could mean a few things one being overfitting. This shows that the model has learned well from the training data but could perform incorrectly as it is given unseen data. This reduces the models accuracy in its predictions and generalisation. A way to avoid this could be to try a model, feeding the model different data sets or simply simplifying the model.
- Accuracy Score 99%. This shows my model was exceptionally good at predicting the data I feed it.
- Precision Scores: 0 (Healthy Loans) = 100%, 1 (High Risk Loans) = 0.85
- Recall Score for borrowers 0 (Healthy Loans) = 99%, Recall Score for borrowers 1 (High Risk Loans) = 91%

## Summary
Overall I got quite high scores in a lot of areas for my model in a variety of areas. Whilst on the surface this might seem great it doesn't nessecarily mean so. For example getting a score of 100% in something would be amazing but in this instance however this is not the case. The 100% could mean a few things one being overfitting. This shows that the model has learned well from the training data but could perform incorrectly as it is given unseen data. This reduces the models accuracy in its predictions and generalisation. A way to avoid this could be to try a model, feeding the model different data sets or simply simplifying the model. This applies especially for the 100% F1 score for the Healthy Loans. Overall though I do belive this would be a very useful model to use despite the flaws I have previously mentioned. 

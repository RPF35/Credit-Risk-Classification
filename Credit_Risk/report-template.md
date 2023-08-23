## Overview of the Analysis

Description

This Credit Risk analysis report uses machine learning to evaluate the performance of regression models attempting to identify whether borrowers have a high enough credit score for a loan. There are 2 models where their performances were compared to find which model is the best. The two variables are labeled "0" for "healthy loan" and "1" for "high-risk" loan.

When creating the models, the dataset was split into features and labels that were and further divided into training and testing sets.

Machine Learning Model 1 was built by a logistic regression model and trained with the original training sets (x_train, y_train), fitting it to the training sets, and using it to generate predictions.

Machine Learning Model 2 was created by resampling the original training data using the RandomOverSampler module, using a logistic regression model and fitting the resampled training sets (x_resample, y_resample) to the model, and generating predictions.

## Results

* Machine Learning Model 1:
  * Model 1 gives an accuracy of 94.4% in predicting the 2 labels. The model is very good at predicting the healthy loans, with both precision and recall scores of 1.00. However, the model's performance in predicting the high-risk loans can be improved. The precision score for high-risk loans is 0.87, indicating that only 87% of actual high-risk loans were predicted correctly. The recall score for high-risk loans is 0.89, showing that the model identified 89% of all high-risk loans in the dataset.



* Machine Learning Model 2:
  * Model 2, trained on the resampled data, has an accuracy of 99.6% in predicting the 2 labels. The model performs well at predicting the healthy loans, with both precision and recall scores of 1.00. The precision score for high-risk loans remains at 0.87, but the recall score has improved to 1.00, indicating that the model can now predicting all high-risk loans in the dataset.

## Summary

Based on the results of the models, model 2 would be the recommended choice to use for predicting both labels. Model 2 has a high precision in predicting high-risk loans while correctly identifying all high-risk loans in the dataset, which is good performance. Model 2, overall, has better accuracy in predicting labels.
# Credit-Risk-Classification

Description

This Credit Risk analysis report uses machine learning to evaluate the performance of regression models attempting to identify whether borrowers have a high enough credit score for a loan. There are 2 models where their performances were compared to find which model is the best. The two variables are labeled "0" for "healthy loan" and "1" for "high-risk" loan.

When creating the models, the dataset was split into features and labels that were and further divided into training and testing sets.

Machine Learning Model 1 was built by a logistic regression model and trained with the original training sets (x_train, y_train), fitting it to the training sets, and using it to generate predictions.

Machine Learning Model 2 was created by resampling the original training data using the RandomOverSampler module, using a logistic regression model and fitting the resampled training sets (x_resample, y_resample) to the model, and generating predictions.
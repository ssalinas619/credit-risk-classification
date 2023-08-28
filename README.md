## credit-risk-classification
## Module 20 Report

# Overview of the Analysis

The purpose of this challenge is to create a model that can identify creditworthiness of borrowers. The dataset used contains historical lending activity from a peer-to-peer lending service. From this dataset we are using loan status as the y value and all the other loan features (loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt) as our x value. These values are then used to compare x (prediction) to y (actual) in a logistic regresion model with the original data and then resampled data.

# Results

* Machine Learning Model 1
  * Description of Model 1 Accuracy, Precision, and Recall scores:
  * Accuracy- The accuracy of the logisistic regression model (using the original data) was about 95% (0.9520479254722232)
  * Precision- The precision for 0 (aka a healthy loan status) was 100% (1.00) while the precision for 1 (aka a high risk loan status) was 85% (0.85)
  * Recall- The recall score for 0 was 99% (0.99) and the recall for 1 was 91% (0.91)


* Machine Learning Model 2
  * Description of Model 2 Accuracy, Precision, and Recall scores:
  * Accuracy- The balanced accuracy of the logisistic regression model (using the resampled training data) was about 95% (0.9494259906569136)
  * Precision- The precision for 0 (aka a healthy loan status) was 100% (1.00) while the precision for 1 (aka a high risk loan status) was 86% (0.86)
  * Recall- The recall score for 0 was 100% (1.00) and the recall for 1 was 90% (0.90)

# Summary

* Looking at both model 1 and 2 we see that the results are fairly similar.
* Model 2 has a better precision and acccuracy if we are focused on '0' as well as better precision for 1. However, the recall for '1' is better in model '1'
* I would recommend model 2 due to the fact that it seems to score slightly higher in most categories.

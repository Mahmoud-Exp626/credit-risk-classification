**# credit-risk-classification**
Using various techniques to train and evaluate a model based on loan risk. Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

**## An overview of the analysis:**
The purpose of this analysis is to use various techniques to train and evaluate a model based on loan risk. We used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

**## The results:**
- The overall accuracy of the model is 0.99, meaning that 99% of the total predictions made by the model were correct.
- For label 0 (healthy loan): Precision is 1.00, meaning that every loan predicted as healthy was indeed healthy. There were no false positives.
- For label 1 (high-risk loan): Precision is 0.87, indicating that 87% of the loans predicted as high-risk were actually high-risk. This means there were some false positives (loans incorrectly classified as high-risk).
- For label 0: Recall is 1.00, which means the model correctly identified all healthy loans. There were no false negatives (healthy loans incorrectly classified as high-risk).
- For label 1: Recall is 0.95, indicating that 95% of the actual high-risk loans were correctly identified. This suggests that the model missed 5% of the high-risk loans (false negatives).

**## A summary:** 
The logistic regression model shows excellent performance in predicting healthy loans, achieving perfect precision and recall. For high-risk loans, while the precision is slightly lower, the recall is still quite high, indicating that the model is effective in identifying most high-risk loans. Overall, the model has a very high accuracy and performs well across both classes, especially when considering the class imbalance. Being that the model was at 99% accuracy, I would recommend this model for use by the company because of such high accuracy rate. 

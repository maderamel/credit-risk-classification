# credit-risk-classification

### Credit Risk Analysis Report

# Overview
The purpose of this report is to recommend a machine learning model that accurately predicts the risk associated with loans. The analysis aims to assist the company in impoving overall credit risk management by using machine learning to make informed decisions regarding loan approvals which would help to minimize potential losses.

# The results
- *Accuracy*: The model's accuracy averaged 99% on both the training and testing datasets. This indicates a high level of correctness in predicting loan loss.

- *Precision*: In both training and testing datasets, the model predictied healthy loans with 100% precision. Unhealthy loans proved to be more difficult, with precision scores of 85% and 88% for training and testing data respectively. Due to the lower precison scores for unhealthy loans, further analysis was conducting by performing oversampling. The goal of oversampling is to address class imbalances by increasing the number of minority class instances to match that of the majority class in order to improve the model's ability to predict minority class instances more precisely. This method showed revealed a 99% precision score at predicting unhealthy loans, further demonstrating the models ability to identify a significant proportion of high risk loans. 

- *Recall*: Recall measures the proportion of correctly predicted high risk loans out of all the instances predicted as high-risk. The high recall score indicates the model's capability to identify the majority of high risk loans, minimizing the chances of missing potential risks.

# Summary
The machine learning model demonstrates strong performance in predicting credit risk associated with loans. The model achieves high accuracy, precision, and recall scores, indicating its effectiveness in identifying both healthy and high risk loans. By incorporating this model into the approval process, the company can minimize the chances of approving high risk loans and thus mitigate potential losses. Additionally, the model's high recall score ensures that a majority of high risk loans are correctly identified, which would enhance the company's risk assessment capabilities. Based on the results, the company is recommended to utilize this machine learning model for credit risk analysis in the approval process. 

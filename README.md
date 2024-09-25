# Credit Risk Classfication 

## Overview of the Analysis

The purpose of this project is to create a logistic regression model to predict the credit risk of borrowers and classify loans into two categories:

0: Healthy loans (low risk of default).
1: High-risk loans (greater likelihood of default).

### Dataset 
The data comes from a peer-to-peer lending services, and includes the following details: loan size, interest rates, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt and loan status (the target variable). The model aims to predict whether a loan will be high risk (1) or healthy (0).


### Key Steps:

1. Data Preparation: The dataset (lending_data.csv) was read into a Pandas DataFrame. The target variable (loan_status) was separated from the features, and the data was split into training and testing sets using train_test_split.

2. Create Logistic Regression Model: A Logistic Regression model was used  to classify loans into the two categotries. The model was fit using the training data (x_train) and (y_train). The predictions for the testing data labels were then saved using the testing feature data (x_test) and the fitted model. Finally, a confusion matrix and classification report were were generated to evauluate the model's performance.  

3. Model Evaluation: A confusion matrix and classification report were were generated to evauluate the model's performance.  

## Results

* Machine Learning Model 1:
   
Accuracy: 99%
Precision for Class 0 (Healthy Loans): 100%
Precision for Class 1 (High-risk Loans): 86%
Recall for Class 0 (Healthy Loans): 99%
Recall for Class 1 (High-risk Loans): 94%
F1-score for Class 0: 100%
F1-score for Class 1: 90%"

## Summary

The Logistic Regression model performed well, with an overall accuracy of 99%. The model was most effective at identifying healthy loans (0), with a perfect precision score of 100% and a recall score of 99%. It also performed well on high-risk loans (1), with a precision of 86% and a recall of 94%.

### Recommendations 

Based on these results, the logistic regression model is recommended for this task. The model predicts healthy loans with a high degree of accuracy, minimizing the risk of incorrectly labeling a healthy loan as high risk. The model also does well in identifying high-risk loans to prevent loan defaults. The precision and recall for high-risk loans show that the model can accurately identify risky borrowers and reduce the likelyhood of missing actual high-risk loans.Ultimately, the model's ability to accurately predict high-risk loans is important for identifying potential defaults, and the high precision for healthy loans ensures that most low-risk loans are correctly classified.

## Acknowledgements
    
    Xpert Learning Assistant was used to answer detailed questions, and assist in debugging.The starter code provided was the base of the report and was modified using course curriculum and activities to fit the requirements of the assignment. The TA and instructor for the course also assisted in adjusting the code during office hours.For more information about the Xpert Learning Assistant, visit [EdX Xpert Learning Assistant](https://www.edx.org/). 

## References

Scikit-learn. (n.d.). Logistic Regression. Retrieved from https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html

Scikit-learn. (n.d.). PCA (Principal Component Analysis). Retrieved from https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html

Scikit-learn. (n.d.). Agglomerative Clustering. Retrieved from https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html

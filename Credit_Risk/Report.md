# Module 12 Report Template

## Overview of the Analysis

The purpose of the analysis is to implement a supervised Machine Learning model that will predict if a loan is healthy or risky. We classify those two category with 0 and 1 respectively.


For this task we used a 77536 line CSV file. The dataset focused on loan size, interest rate, borrower income , debt-to -income ratio, number of accounts, derogatory marks and total debt and loan status. For the latter we had to predict if it's indeed healthy or risky and compare it to the given data.


For the analysis we first had to select labels and features. The chosen label was loan status  and the reamining columns were the features. Then, we splitted the data into training and testing datasets.
Afterwards, we had to implement a Logistic Regression model and fit it with the training data. The next step, was making predictions with te test data.
Lastly, we evaluated the model's perfomrance in terms of accuracy, precision and recall scores.



## Results

- Accuracy: 0.99

- Precision:
    Healthy Loan (0)  : 1.00
    High-Risk Loan (1): 0.84

- Recall
    Healthy Loan (0)  : 0.99
    High-Risk Loan (1): 0.94


## Summary

The model does an outstanding job predicting healthy loans (those represented by 0), with a presicion of 100% and 99% for the recall.
For the high-risk loans (1) however, while it still does good job, there's a decrease in both percentages, giving us 84% precision and %94 recall. These percentages can be a result of the proportion of each type of loans in the dataset, having a considerably larger amount of healthy loans (18765) versus risky ones (619). Having a larger sample of high risk loans could help train the model. Still, having a 99% accuracy for this model is very good. 


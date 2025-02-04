# Module 12 Report Template

## Overview of the Analysis

* Explain the purpose of the analysis.

  The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting loan statuses, specifically distinguishing between healthy loans and high-risk loans.

* Explain what financial information the data was on, and what you needed to predict.

  By assessing the model's accuracy, precision, recall, and F1-score, we can determine how well the model identifies each type of loan and understand its strengths and weaknesses.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

    I used df.info to learn overview of the data and df.head() to print dataframe to see if the analysis went through. 
  
* Describe the stages of the machine learning process you went through as part of this analysis.

  Data read: Called data into python. 
  Data overview: to see if data is appropriate to apply into machine learning. 
  Train-Test Split: Split the dataset into training and testing sets to evaluate the model's performance.
  Model Selection: Choose an appropriate machine learning algorithm (Logistic Regression in this case).
  Model Training: Train the model using the training data.
  Model Evaluation: Evaluate the model's performance using the testing data and metrics like accuracy, precision, recall, and F1-score.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

Train-Test Split: Splits the dataset into training and testing sets to evaluate the model's performance

LogisticRegression: Used for binary classification tasks, such as predicting whether a loan is healthy or high-risk.

Predictions: Makes predictions on the test set.

Accuracy Score: Measures the overall correctness of the model.

Classification Report: Provides detailed metrics like precision, recall, and F1-score for each class.



## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

    * Accuracy score: which is the ratio of correctly predicted instances to the total instances in the test set
    * Precision: Measures the accuracy of the positive predictions. High precision for a class means that when the model predicts that class, it is usually correct.
    * Recall scores: Measures the ability of the model to find all the relevant instances of a class. High recall for a class means that the model correctly identifies most of the actual instances of that class.
    * F1-Scpre: The weighted average of precision and recall. It is useful in need a balance between precision and recall.
    

## Summary

The logistic regression model performs exceptionally well overall, with a high accuracy of 99%. It has excellent precision, recall, and F1-scores for predicting healthy loans (0). For high-risk loans (1), the precision is slightly lower, but recall is high, indicating that the model correctly identifies most high-risk loans. Therefore, to me this is the best performing model. 

* If the primary goal is to minimize financial risk by accurately identifying high-risk loans, improving the precision can be recommended by achieving to adjust the decision threshold or using techniques like oversampling the minority class.

Thank you,Nurmaa


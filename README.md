# Banking_customer_analyses

Problem statement:
Marketing team is trying to maximize the number of customers subscribing to Term Deposit. 
There is too much manual effort with too little result since mostly the customers are randomly contacted. The team needs help to identify customers with the maximum chance of committing.
Goal statement:
help the marketing team to identify customers with highest probability of subscribing.
Dataset:
We have data from previous campaigns with features recorded for customers who subscribed at the end for the specific product.

The approach in solving such cases usually consists of the followings:
1- exploration and visualization of data 
  imbalanced class has been noticed in dependent variables
2-Modelling : 
training the logistic regression and random forest
Tune the hyperparameters
3-data preparation

4-evaluation 
Finalize evaluation metric
F1score, 
Recall
Precision
Accuracy
Confusion matrix![image](https://user-images.githubusercontent.com/25505468/197756433-435bf8f0-ee95-4619-9dc2-fc017222f157.png)

Summary of the results
evaluation was done with logistic regression and random forest
Dataset was imbalanced (majority class: minority class=89:11) thus evaluation metric had to be chosen with care (F1score, confusion matrix, recall, accuracy and precision)
Models with best results:
Compare the performance of the Random Forest, the logistic model, the Naive Bayes and Decision Tree
1- Accuracy score for selected features when we use logistic model is 0.93, when we use Random forest model is 0.97, when we use Naive Bayes model is 0.86 and  when we use Decision Tree model is 0.88
2- Precision score for selected features when we use logistic model is 0.9409, when we use Random forest model is 0.9931, when we use Naive Bayes model is 0.8405 and  when we use Decision Tree model is #### 0.8406
3- recall for selected features when we use logistic model is 0.9098 and when we use Random forest model is 0.9502, when we use Naive Bayes model is 0.89 and  when we use Decision Tree model is 0.9315

Evaluation metric chosen:
The next step after implementing a machine learning algorithm is to find out how effective is the model based on metric and datasets. Different performance metrics are used to evaluate different Machine Learning Algorithms. For example a classifier used to distinguish between images of different objects; we can use classification performance metrics such as, Precision score,accuracy score , recall score and Cross val score etc.
The machine learning model cannot be simply tested using the training set, because the output will be prejudiced, because the process of training the machine learning model has already tuned the predicted outcome to the training dataset. Therefore in order to estimate the generalization error, the model is required to test a dataset which it hasn’t seen yet; giving birth to the term testing dataset.
The machine learning model cannot be simply tested using the training set, because the output will be prejudiced, because the process of training the machine learning model has already tuned the predicted outcome to the training dataset. Therefore in order to estimate the generalization error, the model is required to test a dataset which it hasn’t seen yet; giving birth to the term testing dataset.

Which model has better performance on the test set?
To benchmark and comparing classification scores between Random Forest, the logistic model, the Naive Bayes and Decision Tree, metrics such as accuracy, area under the curve, true positive rate, false positive rate, and precision were analysed. 
To provide statistical quantification as to whether a difference in model performance is conclusive enough to state the difference is significant or if the observed difference is by random chance
Random forest has got better accuracy score compared to logistic,  Naive Bayes and Decision Tree hence we can say that it has better performance








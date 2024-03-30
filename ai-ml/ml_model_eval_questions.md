# Model Evaluation Questions

## Beginner Level

### Question 1: Evaluating a Logistic Regression Model

You are evaluating a logistic regression model's performance on a binary classification problem, aiming to predict whether an email is spam (1) or not spam (0). After testing on a validation set of 200 emails, the following confusion matrix is obtained:

| Actual \ Predicted | Spam (1) | Not Spam (0) |
|--------------------|----------|--------------|
| Spam (1)           | 80       | 20           |
| Not Spam (0)       | 30       | 70           |

**Which metric best represents the model's accuracy?**

A) 0.55  
B) 0.75  
C) 0.80  
D) 0.25  

**Correct Answer:** B

### Question 2: Evaluating Model Performance in Imbalanced Datasets

Consider a dataset containing patient records for a hospital, predicting whether patients will require readmission within 30 days. The dataset is significantly imbalanced, with a higher number of patients not requiring readmission.

**Which metric is most appropriate to evaluate the model's performance?**

A) Accuracy  
B) Precision  
C) Recall  
D) F1 Score  

**Correct Answer:** D

## Intermediate Level

### Question 3: Forecasting Stock Market Direction

A machine learning model is developed to forecast the stock market's direction (up or down) for the next day. The model's performance is evaluated using back-testing with historical data.

**Given the importance of both Type I and Type II errors, which approach provides the most comprehensive understanding of the model's predictive capabilities?**

A) Analyzing the model's ROC curve and calculating the AUC  
B) Calculating the model's accuracy  
C) Focusing solely on the model's precision  
D) Focusing solely on the model's recall  

**Correct Answer:** A

### Question 4: Multi-class Classification Problem in News Categorization

You're working on a multi-class classification problem to categorize news articles into one of five categories. The model achieves a 90% accuracy rate on the training set but only a 60% accuracy rate on the validation set.

**What might be the most probable cause for this discrepancy?**

A) Overfitting  
B) Underfitting  
C) High bias  
D) High variance  

**Correct Answer:** A

### Question 5: Recommendation System for a Movie Streaming Service

In a recommendation system project for a movie streaming service, your model recommends movies to users based on their watching history. You decide to use the Precision@K and Recall@K metrics for model evaluation.

**What does K represent in this context, and why are these metrics useful?**

A) K represents the number of clusters in the dataset, useful for identifying similar movies.  
B) K represents the number of recommendations made to the user, useful for evaluating the model's accuracy in the top recommendations.  
C) K represents the number of features used to train the model, useful for feature selection.  
D) K represents the number of hidden layers in the neural network model, useful for tuning the model's complexity.

**Correct Answer:** B

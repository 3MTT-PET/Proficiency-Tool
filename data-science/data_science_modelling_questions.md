# Predictive Modelling Questions 

## Beginner Level Questions

### Question 1

### Subscription Dataset

| UserID | Age | Income | NumberOfPurchases | Subscribed |
|--------|-----|--------|-------------------|------------|
| U001   | 24  | 55000  | 15                | Yes        |
| U002   | 32  | 45000  | 5                 | No         |
| U003   | 41  | 85000  | 2                 | No         |
| U004   | 29  | 62000  | 20                | Yes        |
| U005   | 36  | 76000  | 3                 | No         |

**Question:** Building a logistic regression model to predict subscription to a premium service based on `Age`, `Income`, and `NumberOfPurchases`, you notice better performance on the training set than the validation set. Which step could improve performance on unseen data?

A) Use a polynomial features transformation to increase complexity.

B) Add more features to increase complexity.

C) Remove the `Income` feature to reduce multicollinearity.

D) Increase the regularization strength to reduce overfitting.

**Correct Answer:** D

---

### Question 2

### Monthly Sales Dataset

| ProductID | ReviewScore | Price | Category | MonthlySales |
|-----------|-------------|-------|----------|--------------|
| P001      | 4.5         | 19.99 | Toy      | 1500         |
| P002      | 3.8         | 89.99 | Kitchen  | 750          |
| P003      | 4.2         | 29.99 | Toy      | 1200         |
| P004      | 4.0         | 15.99 | Decor    | 600          |
| P005      | 3.5         | 45.99 | Outdoor  | 900          |

**Question:** Developing a linear regression model to predict `MonthlySales` based on `ReviewScore` and `Price`, which step is crucial to accurately capture the relationship between features and the target variable?

A) Apply a log transformation to `MonthlySales` to normalize its distribution.

B) Increase the regularization parameter to improve fit to the training data.

C) Create interaction terms between `ReviewScore` and `Price`.

D) Convert `Category` into a numeric feature and include it in the model.

**Correct Answer:** A

---

## Intermediate Level Questions

### Question 3: Tuning a Random Forest Classifier for Customer Churn Prediction

**Question:** When tuning a Random Forest classifier to improve its accuracy in predicting customer churn with a balanced dataset, which hyperparameters should you primarily focus on adjusting?

A) `n_estimators`: Increase the number of trees in the forest.

B) `max_depth`: Reduce the maximum depth of the trees to prevent overfitting.

C) `learning_rate`: Increase the rate at which the model learns, applicable for boosting algorithms.

D) `min_samples_rate`: Adjust the minimum rate required to split an internal node.

**Correct Answers:** A

---

### Question 4

### Health Dataset

| PatientID | Age | BMI  | Diabetic | BloodPressure | TreatmentSuccess |
|-----------|-----|------|----------|---------------|------------------|
| 001       | 45  | 22.4 | No       | Normal        | Yes              |
| 002       | 54  | 27.8 | Yes      | High          | No               |
| 003       | 37  | 31.5 | No       | High          | Yes              |
| 004       | 29  | 24.6 | No       | Normal        | Yes              |
| 005       | 65  | 28.4 | Yes      | High          | No               |

**Question:** Working on a gradient boosting machine (GBM) model to predict `TreatmentSuccess` based on patient characteristics, you notice overfitting. Which step is likely to address this?

A) Increase the `learning rate` to speed up convergence.

B) Decrease the `max_depth` parameter to limit the complexity of individual trees.

C) Increase the `n_estimators` parameter to add more trees to the model.

D) Decrease the `min_samples_leaf` parameter to allow more detailed splitting.

**Correct Answer:** B


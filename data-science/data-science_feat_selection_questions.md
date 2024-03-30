# Feature Selection Questions

## Beginner Level

### Question 1

**Question:** You are developing a model to predict house prices based on various features. The dataset includes features such as `SquareFeet`, `NumberOfBedrooms`, `NumberOfBathrooms`, `AgeOfHouse`, and `ZipCode`.
Which feature selection technique would be most appropriate to identify the most relevant features for predicting house prices?

A) Ignore feature selection and use all features.

B) Apply Recursive Feature Elimination (RFE) to systematically remove features.

C) Perform Principal Component Analysis (PCA) to reduce the dataset dimensionality.

D) Use model-specific feature importance scores to select the top features.

**Correct Answer:** D

---

### Question 2

**Question:**  In a dataset for predicting credit card fraud, features include `TransactionAmount`, `TransactionDateTime`, `CardHolderAge`, `TransactionLocation`, and `MerchantCategory`.
When using a decision tree-based model, which feature is likely to be considered most important for predicting fraud?

A) `TransactionAmount` because higher amounts are often indicative of fraudulent transactions.

B) `TransactionDateTime` because fraud can occur at any time and is not predictive.

C) `CardHolderAge` because people within various age brackets can commit fraud.

D) `TransactionLocation` because some locations may be more prone to fraud.

**Correct Answer:** A

## Intermediate Level

---

### Question 3

**Question:** You're working with a high-dimensional dataset containing genomic data for cancer classification. The dataset includes thousands of gene expression features for each sample.
Given the high dimensionality of the dataset, which feature selection method is most appropriate to improve model performance and interpretability?

A) Perform feature engineering to create new interaction terms between genes.

B) Use a LASSO regression model for its inherent feature selection capabilities.

C) Implement a random forest classifier and select features based on tree depth.

D) Use an ensemble model for its inherent diemnsionality reduction capabilities.

**Correct Answer:** B

---

### Question 4

**Question:**  For a time series forecasting model predicting stock prices, your dataset includes daily prices, volumes, and several technical indicators (e.g., moving averages, RSI, MACD).
What is a critical consideration when selecting features for this time series model?

A) Ensuring features do not introduce future leakage.

B) Selecting features with the highest correlation to the target variable.

C) Using PCA to reduce the number of features before model training.

D) Choosing features based on their importance scores from a previous unrelated model.

**Correct Answer:** A

---

### Question 5

**Question:**  A dataset for predicting customer lifetime value includes features such as `TotalSpend`, `AverageOrderValue`, `NumberOfOrders`, `TotalDiscountsReceived`, and `CustomerSatisfactionScore`.
When addressing multicollinearity before training your model, what step should you take?

A) Increase the number of features to diversify the dataset.

B) Use a correlation matrix to identify and remove highly correlated features.

C) Build a regression model to address the multicollinearity.

D) Randomly select one feature from each set of correlated features without analysis.

**Correct Answer:** B

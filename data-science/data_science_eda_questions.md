# Exploratory Data Analysis Questions

## Beginner Level

### Question 1

#### E-Commerce Dataset

| Date       | ProductID | UnitsSold | Revenue |
|------------|-----------|-----------|---------|
| 2023-01-01 | 1001      | 250       | 5000    |
| 2023-01-01 | 1002      | 150       | 3000    |
| 2023-01-02 | 1001      | 275       | 5500    |
| ...        | ...       | ...       | ...     |

**Question:** You are analyzing a dataset containing daily sales data for an e-commerce company, including columns for `Date`, `ProductID`, `UnitsSold`, and `Revenue`. You aim to understand sales trends over time. Which of the following steps would be most appropriate as a starting point for exploratory data analysis (EDA)?

A) Perform a linear regression analysis to predict future sales.

B) Create a time series plot of `Revenue` over `Date`.

C) Conduct a t-test to compare `UnitsSold` across different products.

D) Use a clustering algorithm to segment the products based on sales data.

**Correct Answer:** B

---

### Question 2

#### Car Sales Dataset

| Make  | Model | Year | MilesDriven | SalePrice | Condition |
|-------|-------|------|-------------|-----------|-----------|
| Ford  | Focus | 2015 | 50000       | 8000      | Good      |
| Chevy | Malibu| 2012 | 75000       | 7000      | Fair      |
| Honda | Civic | 2018 | 30000       | 12000     | Good      |
| ...   | ...   | ...  | ...         | ...       | ...       |

**Question:** You have a dataset from a car dealership containing details about used car sales, including `Make`, `Model`, `Year`, `MilesDriven`, `SalePrice`, and `Condition` (with values like 'Good', 'Fair', and 'Poor'). What would be an effective first step to analyze the relationship between a car's `Condition` and its `SalePrice`?

A) Calculate the Pearson correlation coefficient between `Condition` and `SalePrice`.

B) Perform a logistic regression analysis to predict `Condition` based on `SalePrice`.

C) Apply a k-means clustering algorithm to segment the cars based on `Condition`.

D) Create box plots of `SalePrice` for each category of `Condition`.

**Correct Answer:** D

---

### Question 3

#### Customer Feedback Dataset

| UserID | FeedbackText                                        | Rating | Timestamp          |
|--------|-----------------------------------------------------|--------|--------------------|
| 1      | "Love the new update, especially the UI!"          | 5      | 2023-06-01 10:00:00|
| 2      | "The latest version seems slower than before."     | 3      | 2023-06-01 11:30:00|
| 3      | "Bug in the report generation feature."            | 2      | 2023-06-02 09:15:00|
| ...    | ...                                                | ...    | ...                |

**Question:** Working with a dataset including customer feedback for a software product, featuring `UserID`, `FeedbackText`, `Rating`, and `Timestamp`, your goal is to identify feedback patterns related to software versions. Which method would best aid in exploring patterns in feedback related to software versions?

A) Use natural language processing (NLP) techniques to analyze `FeedbackText` and identify mentions of specific software features.

B) Calculate the mean `Rating` for each `UserID` and analyze the distribution.

C) Perform a linear regression to predict `Rating` based on the length of `FeedbackText`.

D) Create a scatter plot comparing `Rating` and `Timestamp` to visually identify trends.

**Correct Answer:** A

---

### Question 4

#### Retail Store Dataset

| TransactionID | CustomerID | TransactionDate | ProductCategory | AmountSpent |
|---------------|------------|-----------------|-----------------|-------------|
| 001           | 1001       | 2023-05-01      | Electronics     | 300         |
| 002           | 1002       | 2023-05-01      | Clothing        | 150         |
| 003           | 1003       | 2023-05-02      | Groceries       | 75          |
| ...           | ...        | ...             | ...             | ...         |

**Question:** Analyzing a dataset containing transaction records for a retail store, with `TransactionID`, `CustomerID`, `TransactionDate`, `ProductCategory`, and `AmountSpent`, how would you summarize monthly spending patterns by `ProductCategory`?

A) Perform a hierarchical clustering analysis on `AmountSpent` by `ProductCategory`.

B) Use a line graph to identify patterns in `AmountSpent` over time.

C) Create a pivot table with `TransactionDate` as rows, `ProductCategory` as columns, and sum of `AmountSpent` as values, grouped by month. 

D) Calculate the mode of `AmountSpent` for each `ProductCategory` on a monthly basis.

**Correct Answer:** C

---

### Question 5

#### Hospital Stay Dataset Example

| PatientID | Age | Gender | DiagnosisCode | AdmissionDate | DischargeDate |
|-----------|-----|--------|---------------|---------------|---------------|
| P001      | 45  | Male   | D123          | 2023-01-05    | 2023-01-10    |
| P002      | 30  | Female | D234          | 2023-03-12    | 2023-03-15    |
| P003      | 58  | Male   | D345          | 2023-05-20    | 2023-05-22    |
| P004      | 22  | Female | D123          | 2023-07-04    | 2023-07-14    |
| P005      | 65  | Male   | D456          | 2023-09-15    | 2023-09-25    |
| P006      | 75  | Female | D234          | 2023-11-03    | 2023-11-10    |

**Question:** Given a large dataset of patient records from a hospital, including `PatientID`, `Age`, `Gender`, `DiagnosisCode`, `AdmissionDate`, and `DischargeDate`, tasked with identifying trends in hospital stays and diagnoses over time, which EDA technique would you employ?

A) Construct a heatmap to visualize the correlation between `DiagnosisCode` and hospital stay duration.

B) Generate a line graph of average hospital stay duration by month to observe seasonal trends.

C) Use logistic regression to predict the likelihood of extended hospital stays based on `DiagnosisCode`.

D) Apply a decision tree classifier to distinguish between short-term and long-term stays based on `Age` and `Gender`.

**Correct Answer:** B



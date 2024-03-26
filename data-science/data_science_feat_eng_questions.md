# Feature Engineering Questions

## Beginner Level

### Question 1

#### Sales Dataset

| CustomerID | Age | City    | NumPurchases | TotalSpend | MembershipDurationYears |
|------------|-----|---------|--------------|------------|-------------------------|
| 1          | 23  | Austin  | 5            | 150        | 2                       |
| 2          | 37  | Denver  | 8            | 290        | 3                       |
| 3          | 45  | Chicago | 12           | 500        | 4                       |
| 4          | 30  | Austin  | 15           | 450        | 5                       |
| 5          | 22  | Denver  | 7            | 200        | 1                       |

**Question:** Given the dataset above, which feature engineering technique would be most appropriate to prepare the `City` variable for a machine learning model predicting `TotalSpend`?

A) Normalize the `City` column.

B) Perform a log transformation on the `City` column.

C) One-hot encode the `City` column.

D) Calculate the rolling average of `City`.

**Correct Answer:** C

---

### Question 2

#### Retail Store Dataset

| CustomerID | LastPurchaseDate | NumberOfPurchases | AveragePurchaseValue ($) | CustomerSegment |
|------------|------------------|-------------------|--------------------------|-----------------|
| C001       | 2024-02-28       | 5                 | 120.00                   | Loyal           |
| C002       | 2024-03-10       | 2                 | 45.00                    | New             |
| C003       | 2023-12-15       | 1                 | 95.00                    | Churned         |
| C004       | 2024-01-22       | 3                 | 60.00                    | Occasional      |
| C005       | 2024-03-05       | 4                 | 80.00                    | Loyal           |

**Question:** You are preparing a dataset for analyzing customer behavior in a retail store. You want to create a feature that captures the recency of a customer's last purchase. Given the `LastPurchaseDate` and the analysis date of 2024-03-20, which of the following feature engineering steps is most appropriate?

A) Convert `LastPurchaseDate` to a binary feature indicating if the purchase was made in the last 30 days.

B) Calculate the number of days since the last purchase for each customer as a new feature `DaysSinceLastPurchase`.

C) Group customers into bins based on `NumberOfPurchases` and replace `LastPurchaseDate` with this categorical feature.

D) Normalize `AveragePurchaseValue` to have a mean of 0 and a standard deviation of 1.

**Correct Answer:** B

---

## Intermediate Level

### Question 3

#### Housing Dataset

| ListingID | Neighborhood | SquareFeet | Bedrooms | Bathrooms | Price  |
|-----------|--------------|------------|----------|-----------|--------|
| A1        | Suburban     | 1800       | 3        | 2         | 300000 |
| A2        | Urban        | 900        | 2        | 1         | 250000 |
| A3        | Rural        | 2000       | 4        | 2         | 220000 |
| A4        | Suburban     | 1500       | 3        | 1.5       | 280000 |
| A5        | Urban        | 1200       | 2        | 2         | 320000 |

**Question:** You're tasked with creating a model to predict `Price` based on the above dataset. Which feature engineering strategy would best capture the impact of both `Bedrooms` and `Bathrooms` on `Price`?

A) Perform polynomial feature transformation on `Bedrooms` and `Bathrooms`.

B) Standardize `Bedrooms` and `Bathrooms` separately.

C) Combine `Bedrooms` and `Bathrooms` into a single feature by adding them.

D) Create a new feature `BedBathRatio` as the ratio of `Bedrooms` to `Bathrooms`.

**Correct Answer:** D

---

### Question 4

#### Product Sales Dataset

| ProductID | Weight(g) | Color | Material | Price($) | Category |
|-----------|-----------|-------|----------|----------|----------|
| P1001     | 500       | Red   | Plastic  | 19.99    | Toy      |
| P1002     | 1200      | Blue  | Metal    | 89.99    | Kitchen  |
| P1003     | 600       | Green | Plastic  | 29.99    | Toy      |
| P1004     | 300       | Red   | Metal    | 15.99    | Decor    |
| P1005     | 800       | Blue  | Plastic  | 45.99    | Outdoor  |

**Question:** Preparing a dataset for a model predicting product sales based on attributes, you notice the `Weight(g)` feature has a wide range and might skew the model's performance. Which feature engineering step would **most appropriately** address this concern without using one-hot encoding?

A) Replace `Weight(g)` with the median weight of products.

B) Apply a logarithmic transformation to `Weight(g)` to reduce the impact of outliers and scale the data. 

C) Convert `Weight(g)` into categorical bins (e.g., Light, Medium, Heavy) based on weight thresholds.

D) Replace `Weight(g)` with the mean weight of products..

**Correct Answer:** B

---

### Question 5

#### Hospital Stay Dataset

| PatientID | Age | Gender | DiagnosisCode | AdmissionDate | DischargeDate |
|-----------|-----|--------|---------------|---------------|---------------|
| P001      | 54  | Male   | D011          | 2024-03-01    | 2024-03-05    |
| P002      | 29  | Female | D145          | 2024-03-02    | 2024-03-04    |
| P003      | 37  | Male   | D022          | 2024-03-15    | 2024-03-20    |
| P004      | 45  | Female | D145          | 2024-04-01    | 2024-04-09    |
| P005      | 50  | Male   | D011          | 2024-04-15    | 2024-04-22    |

**Question:** In preparing the dataset of patient records from a hospital for a model predicting readmission risk, you decide to create new features based on the existing data. Given the objective and the nature of the data, which feature engineering step would likely be most effective?

A) Convert `AdmissionDate` and `DischargeDate` into a new feature `LengthOfStay` by calculating the number of days between the two dates.

B) Split the date into seasons to capture cyclical patterns.

C) Concatenate `Age` and `Gender` into a single feature to capture demographic patterns.

D) Concatenate `Gender` and `DiagnosisCode` into a single feature.

**Correct Answer:** A

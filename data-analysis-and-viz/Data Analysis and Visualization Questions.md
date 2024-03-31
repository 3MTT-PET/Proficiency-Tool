
# <a name="_m25o8d4nywa5"></a>Data Analysis and Visualisation [54 Questions]
## <a name="_xr9w9ycyws30"></a>Evaluation Curriculum
[Beginner (Entry Level)](#_v6dx88nuk124)

1. [Basic principles of data analysis](#_xzz2r5v8z0zv)
1. [Introduction to data visualisation tools and techniques](#_v5mey3baoj4w)
1. [Understanding and using spreadsheets for data analysis (e.g., Microsoft Excel, Google Sheets)](#_xw6c0t4sdd9p)
1. [Basic SQL queries for data retrieval](#_2mo4kbrovnjy)
1. [Guidelines for effective data visualisation](#_lluh2vlf6tsw)

[Intermediate](#_y0ilw78zbopi)

1. [Intermediate statistical concepts and their applications in data analysis](#_od1np32hpufg)
1. [Data cleaning and preparation techniques](#_jlg73g8xevrc)
1. [Introduction to Python for data analysis](#_56fx1pmj60ei)
1. [Creating interactive dashboards and visualisations with Tableau or Power BI](#_rwtlldefyor7)
1. [Mixed Cognitive Level Question for All Topics](#_z6r5cq14ckes)

[Advanced](#_g9ilf5huy488)

1. [Advanced data modelling and forecasting techniques](#_7o4kgtvbbg5t)
1. [Machine learning applications in data analysis](#_r0cvj1kd7gh)
1. [High-level data visualisation strategies for complex data sets](#_sot2g1kopu02)
1. [Deep dive into specific visualisation tools (e.g., D3.js, advanced Tableau/Power BI features)](#_xjby45128iq2)
1. [Mixed-Cognitive-Level Questions for All Topics](#_kikvk1yqezqv)


## <a name="_v6dx88nuk124"></a>Basic (Entry Level) - [20 Questions]
### <a name="_xzz2r5v8z0zv"></a>Basic Principles of Data Analysis
1\. What is the main purpose of data analysis?
A) To secure data against unauthorised access
B) To convert data into graphical format
C) To extract insights and make correct decisions (Correct)
D) To increase the amount of data storage

Explanation: The primary purpose of data analysis is to extract insights from data which can be used to make informed decisions. The other options relate to different aspects of data management and presentation, not the core purpose of data analysis.

2\. Which statement best explains the term 'data mining'?
A) The physical extraction of raw data from data centres
B) The process of cleaning and organising data in spreadsheets
C) The technique of finding anomalies, patterns, and correlations within large data sets to predict outcomes (Correct)
D) The act of transferring data from one database to another

Explanation: Data mining involves analysing large datasets to find patterns, correlations, and anomalies that can be used to make predictions or informed decisions, which aligns with option C.

3\. You are analysing sales data to identify trends over the past year. Which technique is most appropriate?
A) Data encryption
B) Time series analysis (Correct)
C) Data normalisation
D) Cross-sectional analysis

Explanation: Time series analysis is the appropriate technique for analysing trends over time within a dataset, such as sales data over the past year. The other options do not directly apply to the analysis of trends over time.

4\. Given a dataset with sales figures across different regions and product categories, how would you identify which category performed best in each region?
A) Summarise the total sales by region
B) Calculate the median sales figure for each category
C) Perform a pivot table analysis to summarise data by region and category, then identify the highest values (Correct)
D) Encrypt the sales data for each Visualisation

Explanation: A pivot table analysis allows for the summarization of data across multiple dimensions (in this case, regions, and product categories), making it possible to easily identify which product category performed best in each region.
### <a name="_v5mey3baoj4w"></a>Introduction to Data Visualisation Tools and Techniques
5\. Which tool is widely used for creating interactive data visualisations?
A) Microsoft Word
B) Adobe Photoshop
C) Tableau (Correct)
D) Microsoft Excel

Explanation: Tableau is a powerful and widely used tool for creating interactive and complex data visualisations. While Excel is used for data analysis and can create basic charts, Tableau is specialised for more intricate and interactive visualisations.

6\. How does a 'heatmap' provide insight into a dataset?
A) By encrypting data for secure transfer
B) By highlighting variations across data through colours (Correct)
C) By displaying data in a hierarchical structure
D) By mapping geographical data points on a global scale

Explanation: Heatmaps use colour gradients to represent variations in data, making it easy to understand complex datasets by highlighting patterns, trends, and outliers.

7\. You need to present an annual sales report to highlight trends, performance, and outliers. Which visualisation technique would you use?
A) Line chart to show trends over time (Correct)
B) Pie chart to show a static distribution of sales
C) Histogram to show frequency distribution
D) TreeMap to show hierarchical data

Explanation: Line charts are ideal for visualising data over time, allowing viewers to easily identify trends, performance metrics, and outliers in annual sales data.

8\. Given a dataset on customer feedback scores with variables such as age, gender, and satisfaction level, how would you visualise the relationship between customer satisfaction and age?
A) Create a scatter plot with age on one axis and satisfaction scores on the other (Correct)
B) Use a pie chart to represent satisfaction scores
C) Develop a bar graph to show the frequency of scores
D) Implement a bubble chart without specifying axes

Explanation: A scatter plot is effective for showing the relationship between two quantitative variables, such as age and customer satisfaction scores, allowing for the identification of patterns or correlations.
### <a name="_xw6c0t4sdd9p"></a>Understanding and Using Spreadsheets for Data Analysis
9\. Which function in Excel can be used to calculate the sum of a range of cells?
A) =AVERAGE()
B) =SUM() (Correct)
C) =COUNT()
D) =MAX()

Explanation: The =SUM() function is used to calculate the total sum of a range of cells in Excel. The other functions serve different purposes: =AVERAGE() calculates the average, =COUNT() counts the number of cells that contain numbers, and =MAX() finds the maximum value.

10\. What does the 'VLOOKUP' function do in a spreadsheet?
A) Converts text data into numerical data
B) Looks up and retrieves data from a specific column in a table (Correct)
C) Checks whether a condition is met and returns a value accordingly
D) Finds the highest value in a row or column

Explanation: The 'VLOOKUP' function searches for a value in the first column of a table and returns a value in the same row from a specified column. It is used for vertical lookup.

11\. You have a list of employees' salaries in a spreadsheet and want to increase each salary by 5%. Which approach is most efficient?
A) Use a formula to multiply each cell by 1.05 and paste the result in a new column (Correct)
B) Manually calculate 5% of each salary and add it to the original amount
C) Delete the current salaries and type in the new values
D) Use the 'Sort' function to rearrange the salaries in ascending order

Explanation: Using a formula to multiply each salary by 1.05 (or adding 5%) and placing the result in a new column is the most efficient method to apply a uniform increase across all values.

12\. Given a spreadsheet with sales data including dates, products, and sales figures, how would you determine the month with the highest total sales?
A) Sum up sales figures for each product and compare the totals
B) Use a pivot table to sum sales by month, then identify the month with the highest total (Correct)
C) Manually add up sales for each month and compare the sums
D) Apply a filter to the sales column and sort it from highest to lowest

Explanation: Using a pivot table to aggregate sales by month allows for an efficient analysis of the data to identify which month had the highest total sales. This method simplifies the process and minimises manual calculation errors.
### <a name="_2mo4kbrovnjy"></a>Basic SQL Queries for Data Retrieval
13\. To retrieve all the columns from a table named 'Employees', which SQL statement should be used?
A) SELECT \* FROM Employees (Correct)
B) GET ALL FROM Employees
C) FETCH \* FROM Employees
D) EXTRACT \* FROM Employees

Explanation: The correct SQL statement to retrieve all columns from a table is "SELECT \* FROM Employees". The other options are not valid SQL commands for retrieving data.

14\. What does the 'WHERE' clause do in a SQL query?
A) Specifies the tables to join in a query
B) Defines the columns to be returned by the query
C) Filters rows that meet certain criteria (Correct)
D) Groups rows that have the same values in specified columns

Explanation: The 'WHERE' clause is used in SQL to filter records and retrieve only those rows that satisfy the specified condition.

15\. If you need to find records of employees who joined after January 1, 2020, which SQL query is correct?
A) SELECT \* FROM Employees WHERE JoinDate > '2020-01-01' (Correct)
B) SELECT \* FROM Employees HAVING JoinDate > '2020-01-01'
C) FIND \* FROM Employees WHEN JoinDate > '2020-01-01'
D) GET \* FROM Employees WHERE JoinDate AFTER '2020-01-01'

Explanation: The correct query uses the 'SELECT' statement with a 'WHERE' clause to filter out employees who joined after January 1, 2020. The syntax "> '2020-01-01'" correctly specifies the condition.

16\. You want to analyse the average salary by department from the 'Employees' table. Which SQL statement accomplishes this?
A) SELECT Department, AVG(Salary) FROM Employees GROUP BY Department (Correct)
B) SELECT AVG(Salary), Department FROM Employees ORDER BY Department
C) CALCULATE AVG(Salary) FROM Employees SORT BY Department
D) GET Department, MEAN(Salary) FROM Employees BY Department

Explanation: The correct SQL statement uses "SELECT Department, AVG(Salary) FROM Employees GROUP BY Department" to calculate the average salary within each department. This statement correctly groups the results by department and calculates the average (AVG) salary for each group. The 'GROUP BY' clause is essential for aggregation functions like AVG to return results grouped according to one or more columns.
### <a name="_lluh2vlf6tsw"></a>Guidelines for Effective Data Visualisation
17\. Which principle should be followed to ensure clarity in data visualisation?
A) Use as many colours as possible to make the visualisation attractive
B) Incorporate detailed backgrounds to enhance the visual appeal
C) Keep the design simple and avoid clutter (Correct)
D) Use 3D charts whenever possible to make the data stand out

Explanation: Keeping the design simple and avoiding clutter is a fundamental principle for ensuring clarity in data visualisation. Overcomplicating visuals with excessive colours, backgrounds, or 3D effects can distract from the data's message.

18\. Why is it important to choose the right type of chart for your data?
A) To make the visualisation more complex and detailed
B) To ensure the data is displayed in a scientifically accurate manner
C) To accurately convey the story or insights within the data (Correct)
D) To use as many chart types as possible in a single presentation

Explanation: Choosing the right type of chart is crucial because it ensures that the insights or the story within the data are conveyed accurately and effectively. Different chart types are suited to different kinds of data and analyses, and the right choice helps in communicating the intended message.

19\. You have quarterly sales data for multiple products and want to show sales trends over time. Which visualisation technique would be most effective?
A) Pie chart
B) Line chart (Correct)
C) Stacked bar chart
D) Scatter plot

Explanation: A line chart is most effective for showing trends over time because it can clearly illustrate changes in sales figures across different quarters for multiple products. Pie charts are more suited to showing a composition at a single point in time, stacked bar charts can show parts of a whole over time but might not be as clear for trends, and scatter plots are better for showing relationships between two numerical variables.

20\. Given a dataset with annual revenue and expenses for several departments, how would you identify which department has the most efficient cost-revenue ratio?
A) Create a bar chart comparing total revenue and total expenses for each department
B) Use a line chart to track revenue and expense trends over the years for each department
C) Calculate the cost-revenue ratio for each department and display the results in a ranked bar chart (Correct)
D) Develop a pie chart showing the percentage share of revenue for each department

Explanation: Calculating the cost-revenue ratio for each department and displaying the results in a ranked bar chart is the most efficient method to identify which department has the most efficient cost-revenue ratio. This approach directly addresses the question by focusing on the efficiency metric (cost-revenue ratio) rather than just comparing raw figures or trends.


## <a name="_y0ilw78zbopi"></a>Intermediate [17 Questions]
### <a name="_od1np32hpufg"></a>Intermediate Statistical Concepts and Their Applications in Data Analysis
1\. What does a p-value in hypothesis testing typically represent?
A) The probability of the null hypothesis being true
B) The likelihood of observing the test statistic if the null hypothesis is true (Correct)
C) The probability of the alternative hypothesis being false
D) The percentage of the data that supports the hypothesis

Explanation: The p-value represents the probability of observing the test statistic, or one more extreme, assuming that the null hypothesis is true. It is not a direct measure of the probability that any hypothesis is true or false, but rather a tool for deciding whether the evidence against the null hypothesis is strong enough to reject it.

2\. How does the central limit theorem apply to data analysis?
A) It guarantees that all data distributions are symmetric.
B) It states that the sampling distribution of the sample mean will approximate a normal distribution regardless of the shape of the population distribution, given a sufficient sample size (Correct).
C) It ensures that the mean of any dataset is equal to the median.
D) It asserts that larger datasets always have a normal distribution.

Explanation: The central limit theorem is fundamental to statistical inference, indicating that the sampling distribution of the sample mean approaches a normal distribution as the sample size increases, irrespective of the population's distribution. This theorem supports the validity of inference techniques, such as confidence intervals and hypothesis testing, for a wide range of data distributions.

3\. A data analyst compares the average sales of two stores over the past year to determine if there is a significant difference. Which statistical test is most appropriate for this analysis?
A) Chi-square test
B) Pearson correlation
C) Two-sample t-test (Correct)
D) Linear regression analysis

Explanation: The two-sample t-test is designed to compare the means of two independent groups (in this case, sales from two stores) to see if there is a statistically significant difference between them. The other options are not appropriate for directly comparing the means of two groups.

4\. Given a dataset with numerous variables, how would you identify the variables that most strongly predict a specific outcome?
A) Conduct a series of univariate analyses.
B) Calculate the mean and median for each variable.
C) Perform a multivariate regression analysis (Correct).
D) Use a pie chart to visualise the distribution of each variable.

Explanation: Multivariate regression analysis allows for the examination of the relationship between multiple independent variables and a dependent variable, identifying which predictors have the most significant impact on the outcome. This method enables the analysis of complex relationships within datasets.
### <a name="_jlg73g8xevrc"></a>Data Cleaning and Preparation Techniques
5\. What is a common first step in the data cleaning process?
A) Performing a regression analysis
B) Removing duplicate records (Correct)
C) Applying machine learning models
D) Creating visualisation charts

Explanation: Removing duplicate records is a common initial step in data cleaning, as duplicates can skew analysis results. This foundational task precedes more complex cleaning procedures, ensuring the integrity of the dataset.

6\. Why is it important to handle missing data in a dataset?
A) Missing data can increase the accuracy of predictions.
B) Missing data can lead to biased estimates and invalid conclusions (Correct).
C) Handling missing data increases the computational complexity of models.
D) Missing data typically signifies that no more data cleaning is needed.

Explanation: Missing data, if not properly addressed, can introduce bias, make the analysis less accurate, and lead to invalid conclusions. Various techniques, such as imputation, deletion, or model-based methods, are used to mitigate these issues, depending on the nature and mechanism of the missing value.

7\. You have a dataset with several categorical variables that contain missing values. Which technique is most appropriate for imputing these missing values?
A) Use the mean value of neighbouring data points.
B) Replace missing values with the most frequent category in each variable (Correct).
C) Apply linear regression to predict missing values.
D) Remove all rows that contain any missing values.

Explanation: For categorical variables, a common imputation technique is to replace missing values with the mode, or the most frequent category, of the variable. This approach maintains the distributional properties of the categorical data. Using the mean or linear regression is more appropriate for continuous variables.

8\. In a large dataset, how can you determine if outliers are present and decide on their treatment?
A) Calculate the average value of each variable.
B) Use visualisation tools like box plots to identify outliers (Correct).
C) Perform a chi-square test on each variable.
D) Implement a linear regression model for each variable.

Explanation: Visualisation tools like box plots are effective for identifying outliers by showing the distribution of the data. Once outliers are identified, the analyst must decide how to treat them—whether to keep, remove, or adjust these values—based on their nature and the objectives of the analysis. This decision is crucial, as outliers can significantly impact statistical analyses and model performance.
### <a name="_56fx1pmj60ei"></a>Introduction to Python for Data Analysis
9\. You're working on a data analysis project with numerous CSV files. Which Python library is primarily used to streamline data manipulation and analysis for such tasks?
A) Matplotlib
B) TensorFlow
C) NumPy
D) Pandas (Correct)

Explanation: Pandas is the go-to Python library for data manipulation and analysis, especially suited for working with structured data like CSV files. It offers powerful data structures (like DataFrames) and functions that simplify the process of reading, cleaning, and analyzing data.

10\. You've been tasked with identifying outliers in your dataset. While Python offers multiple libraries, which one provides the foundational array structure that most data analysis tools are built upon, making it essential for numerical operations?
A) Matplotlib
B) TensorFlow
C) NumPy (Correct)
D) Pandas

Explanation: NumPy, known for its powerful N-dimensional array object, is the foundational library for numerical computing in Python. Its arrays provide the backbone for most data analysis and machine learning libraries in Python, making it essential for tasks like identifying outliers through mathematical operations.

11\. After conducting a customer satisfaction survey, you find that some responses are missing. You decide to use Python to impute these missing values based on the column averages. Which code snippet correctly accomplishes this task?
A) df.fillna(df.mean(), inplace=True) (Correct)
B) df.replace(None, df.mean())
C) df.missing\_values('mean')
D) df.set\_values(df.average())

Explanation: The code df.fillna(df.mean(), inplace=True) uses Pandas to replace all missing (NA/null) values in the DataFrame df with the mean of their respective columns. The inplace=True parameter applies the changes directly to the original DataFrame, eliminating the need for assignment.

12\. Your company has collected sales data over the past decade, and you suspect there are seasonal patterns affecting sales performance. Using Python, how would you begin analysing this data for seasonal trends?
A) Utilise Matplotlib to create line charts of sales over time.
B) Implement a seasonal decomposition using statsmodels.tsa.seasonal.seasonal\_decompose to analyse trends, seasonality, and residuals (Correct).
C) Generate random data samples with NumPy for comparison.
D) Perform linear regression with SciPy to model sales trends.

Explanation: The seasonal\_decompose function from the statsmodels library in Python allows for the decomposition of time series data into trend, seasonal, and residual components. This method is particularly useful for identifying and analysing seasonal patterns in sales data, providing insights into how seasonality influences sales performance over time.
### <a name="_rwtlldefyor7"></a>Creating Interactive Dashboards and Visualisations with Tableau or Power BI
13\. Which feature in Power BI allows users to create complex data models from multiple data sources?
A) Power Query
B) Power Pivot (Correct)
C) Power View
D) Power Maps

Explanation: Power Pivot in Power BI is designed for data modelling and allows users to create complex data models by importing data from various sources. It supports large datasets and the creation of sophisticated relationships between tables.

14\. Why is Tableau widely used for creating dashboards and visualisations?
A) It automatically converts all data into pie charts.
B) It has a user-friendly interface and robust data connectivity options, enabling users to easily create interactive and visually appealing dashboards (Correct).
C) It requires extensive programming knowledge, making it suitable only for advanced users.
D) It exclusively supports data from Excel spreadsheets.

Explanation: Tableau is popular for its intuitive drag-and-drop interface and ability to connect to a wide variety of data sources, making it accessible for users with varying levels of technical expertise to create detailed, interactive dashboards and visualisations.

15\. Using Tableau, how would you create a dashboard that updates in real-time as new sales data comes in?
A) Manually update the dataset and dashboard every hour.
B) Use Tableau's live data connection feature to connect to the sales database, allowing the dashboard to update automatically as new data is entered (Correct).
C) Print the dashboard and manually draw in new data points.
D) Export the sales data to a static file and upload it to Tableau daily.

Explanation: Tableau's live data connection feature allows dashboards to automatically update with real-time data changes. By connecting directly to the sales database, any new data entered into the database is immediately reflected in the dashboard, eliminating the need for manual updates and ensuring that the dashboard always displays the most current information.

16\. In Power BI, you've noticed that the dashboard's performance has significantly slowed down after adding multiple complex calculations and data visualisations. How would you systematically identify and address the performance issues?
A) Increase the RAM on your computer to improve performance.
B) Remove all calculations and visualisations to simplify the dashboard.
C) Use Power BI's Performance Analyzer to measure and identify the specific visuals or calculations that are causing the slowdown. Then, optimise or simplify these elements to improve dashboard performance (Correct).
D) Convert all dashboards to static images to ensure they load faster.

Explanation: Power BI's Performance Analyzer tool allows users to track the performance of different elements on a dashboard, such as visuals and DAX calculations. By identifying which components are taking the longest to load, users can pinpoint the source of performance issues and take steps to optimise or simplify these elements, thereby improving the overall performance of the dashboard without necessarily removing all complex calculations and visualisations.
### <a name="_z6r5cq14ckes"></a>Mixed Cognitive Level Question for All Topics
17\. After performing an A/B test on two webpage designs, you obtain a p-value of 0.03. How would you interpret this result in the context of making a decision on which design to implement, and what considerations might you take into account?
A) Implement design A, as it is definitively the better design.
B) Consider design B as superior if it corresponds to the lower p-value, but also evaluate the practical significance and the context of the change before making a final decision (Correct).
C) Ignore the p-value since it does not provide clear guidance on which design is better.
D) Choose the design that was originally preferred, as p-values are unreliable.

Explanation: A p-value of 0.03 suggests that there is a statistically significant difference between the two webpage designs at the commonly used alpha level of 0.05. However, the decision to implement one design over the other should not be based solely on statistical significance. It's important to also consider the practical significance of the difference (e.g., the size of the improvement in user engagement or conversion rates) and other contextual factors, such as the cost of implementing the changes and any potential impacts on the user experience.
### <a name="_ya5lxyq1cpag"></a>
## <a name="_g9ilf5huy488"></a>Advanced [17 Questions]
### <a name="_7o4kgtvbbg5t"></a>Advanced Data Modelling and Forecasting Techniques
1\. Which technique is commonly used for forecasting time series data?
A) Principal Component Analysis (PCA)
B) Linear regression
C) ARIMA (Correct)
D) K-means clustering

Explanation: ARIMA (AutoRegressive Integrated Moving Average) is specifically designed for forecasting time series data, making it the correct choice for this question. PCA is used for dimensionality reduction, linear regression for predicting a continuous outcome variable based on one or more predictor variables, and K-means clustering for partitioning n observations into k clusters.

2\. Why is cross-validation important in predictive modelling?
A) It increases the speed of the model training process.
B) It provides a way to tune the hyperparameters of the model.
C) It helps in assessing the model's ability to generalise to unseen data (Correct).
D) It simplifies complex models automatically.

Explanation: Cross-validation is a technique used to assess how the statistical analysis will generalise to an independent dataset. It is crucial to prevent the model from overfitting to the training data, thereby ensuring that the model has good generalisation capability.

3\. You are developing a forecast model for retail sales data that exhibits strong seasonal patterns. Which approach would you use to incorporate seasonality into your model?
A) Ignore seasonality as it complicates the model.
B) Use a simple moving average to smooth out the series.
C) Apply a seasonal ARIMA model to account for both trend and seasonality (Correct).
D) Use linear regression with sales data as the only predictor.

Explanation: A seasonal ARIMA model is specifically designed to handle data with both trend and seasonality, making it the best choice for forecasting retail sales data that exhibits strong seasonal patterns. It extends the ARIMA model by incorporating seasonal terms.

4\. In analysing a dataset with multiple input features for forecasting, how would you determine which features have the most significant impact on the forecast?
A) Calculate the mean of all input features.
B) Use feature importance scores from a machine learning model like Random Forest or Gradient Boosting (Correct).
C) Perform a univariate analysis of each feature.
D) Visualise the data with a pie chart.

Explanation: Feature importance scores from models like Random Forest or Gradient Boosting provide a quantitative measure of the influence each feature has on the prediction outcome. This method allows for an effective analysis of which features contribute most significantly to the forecasting model.
### <a name="_r0cvj1kd7gh"></a>Machine Learning Applications in Data Analysis
5\. Which algorithm is commonly used for classification tasks?
A) Linear regression
B) ARIMA
C) K-nearest neighbours (Correct)
D) Time series decomposition

Explanation: K-nearest neighbours (KNN) is a simple, versatile algorithm widely used for classification (and regression) tasks. It classifies a data point based on how its neighbours are classified. Linear regression is used for predicting a continuous variable, ARIMA for time series forecasting, and time series decomposition for analysing patterns in time series data.

6\. How does a decision tree determine the feature to split on at each node in a classification task?
A) By selecting the feature with the highest variance.
B) Through random selection.
C) By choosing the feature that results in the highest information gain (Correct).
D) By picking the feature with the fewest missing values.

Explanation: Decision trees use criteria like information gain to choose the feature that best splits the dataset into subsets with the most distinct (homogeneous) classes. This process is repeated at each node until a stopping criterion is met.

7\. A data analyst is tasked with predicting customer churn based on historical user data. Which machine learning model approach would be most appropriate?
A) Clustering analysis
B) Association rule mining
C) Supervised learning classification model (Correct)
D) Principal Component Analysis (PCA)

Explanation: Supervised learning classification models are designed to predict the category (e.g., churn or no churn) of new observations based on historical data with known outcomes. This makes them the most appropriate choice for predicting customer churn.

8\. After training a logistic regression model for a binary classification problem, you notice that the model performs well on the training data but poorly on the test data. What might be the cause?
A) The model is underfitting the training data.
B) There is not enough data to train the model.
C) The model is overfitting the training data (Correct).
D) The test data is too like the training data.

Explanation: Overfitting occurs when a model learns the training data too closely, including its noise and outliers, which leads to poor performance on unseen data. This condition implies that the model has not generalised well from the training data, making it perform poorly on the test data, indicating a gap between its accuracy on the training and test datasets.
### <a name="_sot2g1kopu02"></a>High-Level Data Visualisation Strategies for Complex Data Sets
9\. What is a 'Sankey Diagram' used to visualise?
A) Geographic distributions
B) The flow and quantity of data between different stages or entities (Correct)
C) Correlations between variables
D) Distribution of data over time

Explanation: A Sankey Diagram is specifically used to visualise the flow of data or materials between different stages or entities in a system, highlighting the quantity moving through the system. This makes it an excellent tool for representing complex systems in an easily interpretable manner.

10\. Why might a data analyst use a 'heatmap' to visualise complex datasets?
A) To show data distribution across geographical areas
B) To illustrate the variance of data over time
C) To display the relationship or correlation between two variables
D) To represent the intensity or density of data (Correct)

Explanation: Heatmaps are particularly useful for visualising the intensity or density of data, such as frequency of occurrence or magnitude. By using colour gradients, heatmaps can effectively show variations across the data, helping to identify patterns, trends, and outliers in complex datasets.

11\. Considering a dataset with multiple variables impacting customer satisfaction, how would you visualise the combined effect of these variables to identify key drivers of satisfaction?
A) Use a pie chart for each variable's contribution to satisfaction.
B) Create a line chart showing trends in satisfaction over time.
C) Develop a parallel coordinate plot to visualise multivariate relationships and identify patterns that lead to higher satisfaction (Correct).
D) Implement a scatter plot matrix for pairwise comparison between variables.

Explanation: A parallel coordinates plot is a powerful tool for visualising and analysing multivariate data, allowing analysts to see patterns and relationships across several variables simultaneously. This makes it possible to identify which combinations of variables are associated with higher customer satisfaction levels.

12\. In a dataset visualising sales data across multiple dimensions (time, geography, product category, and sales channels), which strategy would help in identifying underlying patterns effectively?
A) Aggregate all sales data into a single average value for simplicity.
B) Use a multidimensional scaling technique to reduce the dataset to two dimensions for easy visualisation.
C) Employ a combination of interactive dashboards and drill-down capabilities, enabling the exploration of data across different dimensions (Correct).
D) Convert all sales figures to percentages of total sales for uniform comparison.

Explanation: Employing interactive dashboards with drill-down capabilities allows users to explore complex datasets across multiple dimensions interactively. This approach enables the identification of underlying patterns by analysing data from various perspectives and at different levels of granularity.
### <a name="_xjby45128iq2"></a>Deep Dive into Specific Visualisation Tools (e.g., D3.js, Advanced Tableau/Power BI Features)
13\. Which feature in D3.js helps to dynamically generate SVG graphics based on data?
A) CSS transformations
B) HTML5 Canvas
C) Data-driven document manipulation (Correct)
D) JavaScript event listeners

Explanation: D3.js (Data-Driven Documents) uses data to drive the creation and control of dynamic and interactive graphical forms, such as SVG (Scalable Vector Graphics). It leverages data binding to manipulate the Document Object Model (DOM) based on data, making it a powerful tool for creating complex, data-intensive visualisations.

14\. Why would an analyst prefer to use Power BI's DAX (Data Analysis Expressions) over Excel formulas for complex data analysis?
A) DAX is easier to learn than Excel formulas.
B) DAX can handle more data types than Excel.
C) DAX provides more advanced analytical capabilities, particularly for manipulating and analysing data models within Power BI (Correct).
D) DAX formulas can be directly used in Excel without modification.

Explanation: DAX (Data Analysis Expressions) in Power BI offers advanced data manipulation capabilities beyond what is available with standard Excel formulas. It is specifically designed for data modelling and analysis within Power BI, allowing for more sophisticated calculations and analyses on complex data models.

15\. You need to create an interactive web-based dashboard that allows users to explore various data dimensions through selection and filtration. Which tool would you use? 
A) Adobe Illustrator for static infographic design.
B) Microsoft Excel for basic chart creation.
C) D3.js for creating interactive and dynamic data visualisations (Correct).
D) A simple pie chart tool for quick visualisations.

Explanation: D3.js is a powerful JavaScript library that enables developers to create complex, interactive, and dynamic data visualisations in the web browser. It is especially suited for building web-based dashboards that require user interaction, such as selection and filtration, to explore data across multiple dimensions. Unlike tools designed for static or basic visualisations, D3.js provides the flexibility and functionality needed for comprehensive, interactive data exploration.

16\. After implementing several advanced visualisations in Tableau to showcase sales performance metrics, you notice some visualisations take significantly longer to load than others. How would you systematically identify and address the performance issues in your Tableau dashboard?
A) Reduce the complexity of all visualisations across the dashboard to improve load times uniformly.
B) Utilise Tableau's Performance Recording feature to identify which visualisations are causing delays and optimise them by simplifying complex calculations, reducing data density, or adjusting their design (Correct).
C) Convert all interactive visualisations to static images to ensure they load faster.
D) Increase the hardware specifications of the server hosting the Tableau dashboard.

Explanation: Tableau's Performance Recording feature allows users to diagnose and understand the performance of their dashboards. By recording and analysing which actions or visualisations take the most time to load, users can pinpoint specific areas for optimisation. This targeted approach is more efficient than uniformly simplifying or converting visualisations, as it addresses the root causes of performance issues without sacrificing the dashboard's analytical depth or interactivity.

17\. Your team is tasked with developing a predictive model to forecast future product demand, incorporating machine learning for accuracy, and visualising the results to identify trends and inform decision-making. After building the model and creating the visualisations, how would you ensure the results are accurately interpreted and actionable for the strategic planning team?
A) Limit the visualisations to simple line charts to avoid overcomplicating the analysis.
B) Provide a detailed report explaining the predictive model, its accuracy metrics, and interpreting the visualisations with clear insights and recommendations (Correct).
C) Only share the raw output of the machine learning model with the team to ensure data purity.
D) Use complex machine learning terminology when discussing the model to highlight its sophistication.

Explanation: Providing a detailed report that not only presents the predictive model and its accuracy but also interprets the visualisations with actionable insights ensures that the strategic planning team can make informed decisions. This approach bridges the gap between complex data analysis and practical strategic planning, making the results both accessible and actionable. Simplifying the information too much or focusing solely on technical details can hinder effective communication and the applicability of the analysis to real-world decision-making.







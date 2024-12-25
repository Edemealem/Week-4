# Week 2- Project Overview
This project consists of Jupyter Notebooks and scripts designed to perform various data analysis tasks related to the week 2 challenges.

## Completed Steps

1. **Task 1 - User Overview Analysis**:
- Conducted a User Overview Analysis on a telecom dataset to understand customer behavior.
- Identified the top 10 handsets used by customers.
- Determined the top 3 handset manufacturers based on usage.
- Listed the top 5 handsets for each of the top 3 manufacturers.
- Provided a short interpretation of the findings and recommendations for marketing teams.
### 1.1. Task 1.1 - User Behavior Overview
### 1.2 Task 1.2 - Exploratory Data Analysis (EDA
## Data Description
- Described the dataset and displayed the data types of each variable.

## Data Cleaning
- Handled missing values by replacing them with the mean for numeric columns.
- Identified and treated outliers using methods like Z-score.

## Variable Transformations
- Calculated the total duration for all sessions.
- Segmented users into deciles based on total session duration.
- Computed `Total DL+UL` data for each user.

## Basic Metrics Analysis
- Analyzed basic metrics (mean, median, etc.) for the dataset to understand user behavior patterns.

## Univariate Analysis
- Conducted non-graphical analysis by computing dispersion parameters (mean, median, std, min, max).
- Performed graphical analysis using histograms and box plots to visualize distributions and identify outliers.

## Bivariate Analysis
- Explored the relationship between each application’s data usage and `Total DL+UL`.
- Computed the correlation matrix for relevant application data and interpreted the findings.
- Visualized relationships using scatter plots for each application against `Total DL+UL`.

## Correlation Analysis
- Computed a correlation matrix for selected application data (e.g., Social Media, Google, Email, YouTube, Netflix, Gaming, Other) and interpreted the results.

## Dimensionality Reduction
- Performed Principal Component Analysis (PCA) to reduce dimensionality and provide insights on the most significant variables driving data variance.

# Task 2 - User Engagement Analysis

## Engagement Metrics
The following metrics will be tracked:
- **Session Frequency**: Number of sessions per user.
- **Duration of Sessions**: Total time spent per session.
- **Total Traffic**: Combined download and upload traffic in bytes.

## Steps

### 2.1 Analysis Steps
1. **Aggregate Metrics**:
   - Calculate the above metrics per customer ID (MSISDN).
   - Identify the top 10 customers for each engagement metric.

2. **Normalize and Cluster**:
   - Normalize each engagement metric.
   - Apply k-means clustering (k=3) to classify customers into three engagement groups.

3. **Cluster Analysis**:
   - Compute minimum, maximum, average, and total non-normalized metrics for each cluster.
   - Visualize and interpret the results.

4. **Application Engagement**:
   - Aggregate total traffic per application.
   - Identify the top 10 most engaged users for each application.

5. **Visualization**:
   - Plot the top 3 most used applications using appropriate charts.

6. **K-Means Optimization**:
   - Determine the optimal value of k using the elbow method.
   - Interpret the findings.

## Conclusion
This analysis provides valuable insights into user engagement, helping telecom companies enhance their services and allocate resources more effectively.

## Requirements

- Python 3.10.12
- matplotlib
- pandas: 2.2.2
- numpy: 1.26.4
- seaborn: 0.13.2
- PCA
- sqlalchemy

## How to Run

1. Open `Task01.ipynb` in Google Colab.
2. connect to postgresql
3. Run the notebook cells sequentially.

## Conclusion

This analysis provides insights on the data provided

## License

This project is licensed under @Edeme
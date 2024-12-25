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
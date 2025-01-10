# Week 4 - Project Overview

This project explores customer purchasing behavior and predicts store sales using machine learning and deep learning techniques. The final goal is to serve predictions via a web interface.

## Objectives

- **Explore Customer Purchasing Behavior**
- **Predict Store Sales**
- **Implement Machine Learning and Deep Learning Approaches**
- **Serve Predictions on a Web Interface**

## Task 1: Exploration of Customer Purchasing Behavior

### Key Steps Taken

1. **Data Cleaning**:
   - Built pipelines to handle outliers and missing data.

2. **Exploratory Data Analysis (EDA)**:
   - Conducted visualizations to understand data interactions and trends related to customer behavior.

3. **Key Questions Addressed**:
   - Examined the impact of promotions, holidays, and competitor distance on sales.
   - Analyzed seasonal purchasing behaviors and customer trends.

4. **Deliverables**:
   - An exploratory analysis notebook (`Task 1.ipynb`) located in the `notebooks` folder, providing insights and visualizations.

### Logging

- Implemented logging for traceability and reproducibility.

## Task 2: Prediction of Store Sales

### Overview

The goal of this task is to predict daily sales in various stores up to 6 weeks in advance. Accurate predictions will help the company plan for inventory and staffing effectively.

### Key Steps

1. **Preprocessing**:
   - Cleaned data by converting non-numeric columns to numeric and handling missing values.
   - Extracted features from datetime columns, including weekdays, weekends, and days to/from holidays.
   - Scaled the data using Standard Scaler from `sklearn`.

2. **Building Models**:
   - Focused on regression models using sklearn pipelines, starting with tree-based algorithms like Random Forest Regressor.
   - Utilized pipelines for a modular and reproducible modeling process.

3. **Choosing a Loss Function**:
   - Selected an appropriate loss function to evaluate model performance and provided justification for the choice.

### Requirements

- **Python**: 3.10.12
- **Libraries**:
  - `matplotlib`
  - `pandas`: 2.2.2
  - `numpy`: 1.26.4
  - `seaborn`: 0.13.2
  - `jupyter`

## How to Run

1. **Clone the Repository**:

   ```bash
   git clone <URL>
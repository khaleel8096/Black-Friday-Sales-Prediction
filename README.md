# Black-Friday-Sales-Prediction
![alt text](https://searchengineland.com/figz/wp-content/seloads/2014/12/black-friday1-ss-1920.jpg "Black Friday Sales Prediction")

## Overview
This project focuses on predicting customer purchase behavior for a retail company, "ABC Private Limited." The dataset contains purchase summaries for selected high-volume products, along with customer demographics, product details, and total purchase amounts from the last month. The goal is to build a model that predicts the purchase amount of customers against various products.

## Tasks to Perform
The following tasks are to be performed as part of the project:

### Data Preprocessing
1. Check basic statistics of the dataset.
2. Check for missing values in the data.
3. Check for unique values in the data.

### Exploratory Data Analysis (EDA)
1. Perform univariate and bivariate analysis w.r.t the Purchase column.
2. Analyze the distribution of the purchase amount.
3. Check for outliers.
4. Analyze purchase behavior based on gender, marital status, occupation, city, age group, etc.
5. Drop unnecessary fields.
6. Convert categorical data into integers using the map function.
7. Handle missing values, rename columns, and fill NaN values.
8. Map range variables into integers (e.g., 'Age' column).

### Data Visualization
1. Visualize individual columns.
2. Plot Age vs Purchased.
3. Plot Occupation vs Purchased.
4. Plot Product Category 1 vs Purchased.
5. Plot Product Category 2 vs Purchased.
6. Plot Product Category 3 vs Purchased.
7. Create a pie chart for City Category.
8. Explore other possible plots.

### Machine Learning Modeling
1. Split the data into training and testing sets.
2. Implement Linear Regression, Decision Tree Regressor, Random Forest Regressor, and XGBoost Regressor models.
3. Evaluate model performance using metrics like MAE, MSE, RMSE, and R-squared.

## Usage
1. Clone the repository:

   ```bash
   git clone https://github.com/khaleel8096/Black-Friday-Sales-Prediction.git
   cd Black-Friday-Sales-Prediction
jupyter notebook Black-Friday-Sales-Prediction.ipynb

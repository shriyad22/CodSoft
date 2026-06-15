# Sales Prediction Using Python

## Overview

This project predicts product sales based on advertising expenditures across different media channels such as TV, Radio, and Newspaper. Using Machine Learning techniques, the model analyzes advertising data and forecasts future sales to support business decision-making.

This project was completed as part of the CodSoft Data Science Internship.

---

## Problem Statement

Businesses invest heavily in advertising through multiple channels. Understanding how advertising budgets impact sales helps organizations optimize marketing strategies and maximize return on investment.

The objective of this project is to build a Machine Learning model capable of predicting sales using advertising expenditure data.

---

## Dataset Features

| Feature   | Description                     |
| --------- | ------------------------------- |
| TV        | TV advertising budget           |
| Radio     | Radio advertising budget        |
| Newspaper | Newspaper advertising budget    |
| Sales     | Product sales (Target Variable) |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

* Load advertising dataset.

### 2. Data Exploration

* Examine dataset structure.
* Statistical summary.
* Missing value analysis.

### 3. Data Visualization

* Pair Plot
* Correlation Heatmap
* Distribution Plots
* Scatter Plots

### 4. Data Preprocessing

* Feature selection
* Data cleaning

### 5. Model Building

* Train-Test Split
* Linear Regression Model

### 6. Model Evaluation

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 7. Prediction

* Sales prediction for new advertising budgets.

---

## Generated Visualizations

* pairplot.png
* heatmap.png
* actual_vs_predicted.png
* regression_plot.png

---

## Results

The Linear Regression model successfully predicts sales using advertising expenditure data. Evaluation metrics demonstrate the model's effectiveness in understanding the relationship between marketing investments and sales performance.

---

## Business Insights

* TV advertising has the strongest influence on sales.
* Radio advertising contributes positively to sales growth.
* Newspaper advertising has comparatively lower impact.
* Optimizing advertising allocation can improve business revenue.

---

## Future Improvements

* Use advanced algorithms such as Random Forest and XGBoost.
* Hyperparameter tuning.
* Cross-validation.
* Deployment using Flask or Streamlit.
* Real-time sales forecasting dashboard.

---

## Author

Shriya Deshmukh

Artificial Intelligence & Data Science Student

CodSoft Data Science Internship

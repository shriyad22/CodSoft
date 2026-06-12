# Movie Rating Prediction

## Overview
This project predicts movie ratings using Machine Learning techniques based on features such as genre, director, actors, year, duration, and votes. The dataset was preprocessed, cleaned, and used to train multiple regression models for rating prediction.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Models Implemented
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Data Preprocessing
- Removed missing target values
- Handled missing data
- Converted categorical features into numerical values using Label Encoding
- Converted Year, Duration, and Votes into numeric format
- Performed train-test split for model evaluation

## Data Visualization
- Distribution of Movie Ratings
- Feature Importance Analysis

## Results

| Model | R² Score |
|---------|---------|
| Linear Regression | 0.10 |
| Decision Tree Regressor | -0.23 |
| Random Forest Regressor | 0.35 |

## Features Used
- Movie Name
- Year
- Duration
- Genre
- Votes
- Director
- Actor 1
- Actor 2
- Actor 3

## Conclusion
Among the implemented models, Random Forest Regressor achieved the best performance and provided the most accurate movie rating predictions. The project demonstrates the complete machine learning workflow, including data preprocessing, visualization, model training, evaluation, and prediction.



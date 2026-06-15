# Credit Card Fraud Detection Using Machine Learning

## Project Overview

Credit card fraud is one of the major challenges faced by financial institutions. The objective of this project is to build a Machine Learning model that can accurately identify fraudulent credit card transactions and distinguish them from genuine transactions.

This project uses data preprocessing, class imbalance handling, and machine learning techniques to detect fraud effectively.

---

## Objective

The main goal of this project is to:

- Analyze credit card transaction data
- Handle highly imbalanced data
- Build a fraud detection model
- Evaluate model performance using various metrics
- Visualize results through plots and graphs

---

## Dataset

The dataset contains anonymized credit card transaction records with the following characteristics:

- Numerical features generated through PCA transformation
- Transaction Amount
- Transaction Time
- Class (Target Variable)

### Target Variable

- 0 → Genuine Transaction
- 1 → Fraudulent Transaction

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## Project Workflow

### 1. Data Collection
- Loaded the credit card transaction dataset.

### 2. Data Exploration
- Checked dataset shape and statistics.
- Examined class distribution.
- Identified imbalance in fraud and genuine transactions.

### 3. Data Preprocessing
- Checked for missing values.
- Scaled transaction amount using StandardScaler.

### 4. Handling Class Imbalance
- Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.

### 5. Model Building
- Implemented Logistic Regression for fraud classification.

### 6. Model Evaluation
The model was evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## Visualizations

The project includes:

- Class Distribution Plot
- Confusion Matrix
- ROC Curve

---

## Results

The trained model successfully identifies fraudulent transactions while maintaining strong classification performance.

Key evaluation metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

---

## Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── creditcard.csv
├── README.md
├── class_distribution.png
├── confusion_matrix.png
└── roc_curve.png
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Handling imbalanced datasets
- Fraud detection techniques
- Machine Learning model development
- Model evaluation and visualization
- End-to-end Data Science workflow

---

## Conclusion

This project demonstrates how Machine Learning can be used to detect fraudulent credit card transactions effectively. By applying SMOTE for class balancing and Logistic Regression for classification, the model provides reliable fraud detection performance and highlights the importance of data-driven decision-making in financial security.

---


Artificial Intelligence & Data Science Student

Data Science Intern

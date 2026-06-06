# Water Quality Prediction Using Machine Learning: A Comparative Analysis

## Project Overview

Water quality is a critical factor in determining whether water is safe for human consumption. Poor water quality can lead to serious health issues and environmental problems.

This project uses Machine Learning techniques to predict whether water is **Potable (Safe for Drinking)** or **Not Potable (Unsafe for Drinking)** based on various physicochemical properties of water.

The main objective of this project is not only to predict water potability but also to compare the performance of multiple machine learning algorithms and identify the most effective model for this classification task.

---

## Dataset Description

The dataset contains several water quality parameters that influence water potability.

### Features

| Feature | Description |
|----------|------------|
| pH | Measures the acidity or alkalinity of water |
| Hardness | Amount of dissolved calcium and magnesium |
| Solids | Total dissolved solids in water |
| Chloramines | Disinfectant used in water treatment |
| Sulfate | Concentration of sulfate compounds |
| Conductivity | Ability of water to conduct electricity |
| Organic Carbon | Amount of organic matter present |
| Trihalomethanes | Chemical compounds formed during water treatment |
| Turbidity | Measure of water clarity |

### Target Variable

| Value | Meaning |
|---------|---------|
| 0 | Not Potable |
| 1 | Potable |

---

## Data Preprocessing

Before training the models, the dataset undergoes several preprocessing steps:

1. Handling missing values
2. Removing duplicate records
3. Converting data into appropriate formats
4. Splitting the dataset into training and testing sets
5. Feature scaling using StandardScaler

These steps improve data quality and help machine learning algorithms perform effectively.

---

## Machine Learning Models Used

This project compares four supervised machine learning algorithms.

### 1. Logistic Regression

**Why it is used:**
- Simple and interpretable classification algorithm
- Works well as a baseline model
- Efficient for binary classification problems

### 2. K-Nearest Neighbors (KNN)

**Why it is used:**
- Instance-based learning algorithm
- Classifies samples based on similarity to neighboring data points
- Useful for understanding local patterns in the dataset

### 3. Support Vector Machine (SVM)

**Why it is used:**
- Effective in high-dimensional spaces
- Creates an optimal decision boundary between classes
- Often provides strong classification performance

### 4. Random Forest

**Why it is used:**
- Ensemble learning technique
- Combines multiple decision trees
- Reduces overfitting
- Generally provides higher accuracy and robustness

---

## Model Evaluation Metrics

The models are evaluated using multiple performance metrics:

### Accuracy

Measures the proportion of correctly classified instances.

### Precision

Measures how many predicted positive samples are actually positive.

### Recall

Measures how many actual positive samples are correctly identified.

### F1 Score

Harmonic mean of Precision and Recall.

### Confusion Matrix

Provides detailed insight into:
- True Positives
- True Negatives
- False Positives
- False Negatives

### ROC Curve

The Receiver Operating Characteristic (ROC) Curve evaluates a model's ability to distinguish between classes across different threshold values.

---

## Model Comparison

A comparative analysis is performed to determine the most effective model for predicting water potability.

Each model is evaluated based on:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve

The comparison allows us to identify:

- Which model achieves the highest prediction accuracy
- Which model balances precision and recall effectively
- Which model generalizes best on unseen data

The model with the strongest overall performance is selected as the best model for water quality prediction.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Scaling
4. Model Training
5. Performance Evaluation
6. Model Comparison
7. Best Model Selection

---

## Conclusion

This project demonstrates how multiple machine learning algorithms can be applied to a real-world water quality dataset. By comparing different classification techniques, we can determine the most suitable model for predicting water potability and gain insights into the effectiveness of various machine learning approaches.

# Wildfire Risk Prediction Using Machine Learning

## Project Overview

This project analyzes wildfire patterns in New Mexico using machine learning and historical wildfire datasets. The analysis focuses on identifying environmental and wildfire-related patterns associated with large fire events while demonstrating a complete machine learning workflow including preprocessing, exploratory analysis, classification modeling, and evaluation.

As team leader, responsibilities included coordinating project direction, organizing analytical workflows, guiding model evaluation, and integrating results across multiple project phases.

---

## Business Problem

Wildfires create significant environmental, economic, and public safety challenges across the Southwestern United States. This project was designed to explore wildfire occurrence patterns and develop predictive classification models capable of identifying higher-risk wildfire events using historical wildfire records and environmental indicators.

---

## Tools & Technologies

- Python
- Pandas & NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib & Seaborn
- Machine Learning
- Exploratory Data Analysis (EDA)
- Classification Modeling
- Data Mining

---

## Machine Learning Models

The following machine learning models and approaches were explored throughout the project:

- Logistic Regression
- Random Forest Classification
- K-Nearest Neighbors (KNN)
- Threshold Tuning
- Confusion Matrix Evaluation
- Feature Engineering & Preprocessing

---

## Key Areas of Analysis

- Wildfire frequency trends across New Mexico
- Fire size distribution analysis
- Wildfire cause analysis
- Large fire classification modeling
- Precision vs. recall tradeoff evaluation
- Model performance comparison
- Threshold tuning for wildfire detection optimization

---

## Visualizations & Insights

### Fire Causes in New Mexico

Analyzes the most common wildfire causes across New Mexico. Lightning represented the leading cause of wildfire incidents, followed by miscellaneous and debris burning causes.

### Fire Size Distribution

Shows the distribution of wildfire sizes across New Mexico. Most fires were relatively small, while a limited number of extreme wildfire events created a highly skewed distribution.

### Number of Fires Annually

Displays yearly wildfire occurrence trends across New Mexico between 1992–2015, highlighting fluctuations in wildfire activity over time.

### Classifier Performance Comparison

Compares Logistic Regression, Random Forest, and KNN classification models using metrics such as accuracy, precision, recall, and F1 score.

### KNN Confusion Matrix

Evaluates KNN classification performance and demonstrates challenges related to class imbalance and positive wildfire event detection.

### Random Forest Confusion Matrix

Illustrates Random Forest model performance, showing stronger precision but lower recall when identifying large wildfire events.

### Tuned Logistic Regression

Demonstrates threshold tuning improvements applied to Logistic Regression in order to balance wildfire detection recall and false positive reduction.

---

## Repository Structure

```text
images/        -> Charts, visualizations, and confusion matrices
notebook/      -> Jupyter notebooks and ML workflows
report/        -> Project reports and documentation
```

---

## Project Outcome

The project demonstrated the challenges associated with wildfire prediction due to class imbalance and environmental variability. Logistic Regression with threshold tuning produced the most balanced wildfire detection performance, while Random Forest achieved higher precision at the cost of lower recall.

The analysis reinforced the importance of evaluating multiple machine learning metrics rather than relying solely on overall accuracy when working with high-risk environmental prediction problems.

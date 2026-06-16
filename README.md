# E-Commerce Cart Abandonment Prediction

## Project Overview

Cart abandonment is a major challenge in e-commerce, leading to significant revenue loss for online retailers. This project develops machine learning models to predict whether a customer is likely to abandon their shopping cart before completing a purchase.

The goal is to identify at-risk customers early and provide actionable insights that can help businesses improve conversion rates and customer retention strategies.

---

## Business Problem

A large percentage of online shoppers add products to their cart but leave without completing the purchase. Understanding and predicting cart abandonment allows businesses to:

* Reduce lost sales opportunities
* Improve customer experience
* Design targeted marketing campaigns
* Increase conversion rates

This project applies predictive analytics to classify customer sessions as either:

* Purchase Completed
* Cart Abandoned

---

## Dataset

The dataset contains customer shopping session information, including:

* Customer demographics
* Browsing behavior
* Session activity
* Product interactions
* Purchase outcomes

Target Variable:

**Abandoned**

* 1 = Cart Abandoned
* 0 = Purchase Completed

---

## Objectives

* Predict customer cart abandonment using machine learning.
* Compare multiple classification models.
* Handle class imbalance effectively.
* Identify the most important factors contributing to abandonment.
* Generate actionable business insights.

---

## Tools & Technologies

### Programming

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Imbalanced-Learn (SMOTE)
* Matplotlib
* Seaborn

### Machine Learning Techniques

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier
* Hyperparameter Tuning
* Feature Importance Analysis

---

## Project Workflow

### 1. Data Preparation

* Data cleaning
* Missing value handling
* Feature encoding
* Feature scaling
* Target variable creation

### 2. Exploratory Data Analysis (EDA)

* Class distribution analysis
* Customer behavior analysis
* Feature exploration
* Data visualization

### 3. Handling Class Imbalance

Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset and improve model performance.

### 4. Model Development

Built and compared:

* Logistic Regression
* Random Forest
* XGBoost

### 5. Hyperparameter Optimization

Used:

* RandomizedSearchCV

to identify optimal model configurations.

### 6. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

### 7. Explainability

Used feature importance techniques to identify the factors most strongly associated with cart abandonment.

---

## Key Findings

* Customer behavior patterns can be used to effectively predict cart abandonment.
* Ensemble models outperformed baseline models.
* Certain browsing and engagement features had a strong influence on abandonment likelihood.
* Class balancing significantly improved model performance on minority-class detection.

---

## Business Impact

The model can help e-commerce businesses:

* Identify customers likely to abandon their carts.
* Trigger personalized offers and reminders.
* Improve marketing efficiency.
* Increase sales conversions.
* Reduce revenue loss from abandoned sessions.

---

## Results

The project successfully developed predictive models capable of identifying cart abandonment behavior with strong classification performance.

Model comparison was conducted using multiple evaluation metrics to ensure robust and reliable results.

---

## Future Improvements

* Real-time abandonment prediction
* Customer segmentation
* Deep learning approaches
* Recommendation system integration
* Deployment through a web application or API

---

## Repository Structure

```text
├── data/
├── notebooks/
├── models/
├── images/
├── E_Commerce_Cart_Abandonment_Prediction.ipynb
├── requirements.txt
└── README.md
```

---

## Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning
* Model Evaluation
* Hyperparameter Tuning
* Class Imbalance Handling
* Business Analytics
* Predictive Modelling

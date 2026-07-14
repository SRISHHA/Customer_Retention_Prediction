# Customer Segmentation and Retention Prediction using Machine Learning

## Overview

This project focuses on **customer segmentation and retention prediction** using machine learning techniques. The objective is to analyze customer purchasing behavior, group similar customers into meaningful segments, and build a predictive model that can assist businesses in developing targeted marketing strategies.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, supervised machine learning, and model evaluation.

---

# Problem Statement

Understanding customer behavior is essential for businesses to improve customer satisfaction, increase sales, and maximize marketing effectiveness.

Rather than treating every customer the same, organizations can segment customers into different groups based on purchasing patterns and demographics.

This project aims to:

- Analyze customer characteristics
- Identify meaningful customer segments
- Build a predictive model for customer classification
- Support data-driven marketing decisions

---

# Dataset

**Dataset:** Mall Customers Dataset

The dataset contains customer information including:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

These features are used to identify customer purchasing patterns and create customer segments.

---

# Project Workflow

## 1. Data Collection

- Loaded the Mall Customers dataset
- Explored dataset structure
- Examined feature types and distributions

---

## 2. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand customer characteristics.

### Analysis Included

- Customer age distribution
- Gender distribution
- Annual income distribution
- Spending score analysis
- Correlation analysis
- Feature relationships

---

## 3. Data Preprocessing

The preprocessing pipeline included:

- Removing unnecessary columns
- Handling missing values
- Detecting and treating outliers
- Encoding categorical variables
- Feature scaling

---

## 4. Feature Engineering

Prepared the dataset for machine learning by:

- Encoding categorical features
- Standardizing numerical variables
- Selecting relevant features for clustering and prediction

---

## 5. Customer Segmentation

Applied clustering techniques to group customers with similar purchasing behavior.

### Clustering Process

- Feature Scaling
- Cluster Formation
- Customer Group Assignment

Example customer segments include:

- High Income – High Spending
- High Income – Low Spending
- Low Income – High Spending
- Low Income – Low Spending
- Average Customers

These segments help businesses create targeted marketing campaigns.

---

## 6. Predictive Modeling

After customer segmentation, the dataset was split into training and testing sets.

### Workflow

- Train-Test Split
- Model Building
- Model Training
- Prediction
- Performance Evaluation

The trained model predicts customer classifications based on their demographic and purchasing characteristics.

---

# Project Architecture

```text
                Mall Customers Dataset
                         │
                         ▼
                Data Preprocessing
                         │
        ┌────────────────────────────────┐
        │ Remove Missing Values          │
        │ Handle Outliers                │
        │ Encode Categorical Features    │
        │ Feature Scaling                │
        └────────────────────────────────┘
                         │
                         ▼
             Exploratory Data Analysis
                         │
                         ▼
             Customer Segmentation
                 (Clustering)
                         │
                         ▼
             Feature Engineering
                         │
                         ▼
              Train-Test Split
                         │
                         ▼
           Machine Learning Model
                         │
                         ▼
                Model Evaluation
                         │
                         ▼
             Customer Prediction
```

---

# Machine Learning Pipeline

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Handling
      │
      ▼
Outlier Detection
      │
      ▼
Feature Encoding
      │
      ▼
Feature Scaling
      │
      ▼
Customer Clustering
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Model Testing
      │
      ▼
Performance Evaluation
```

---

# Exploratory Data Analysis

The notebook includes visualizations such as:

- Customer age distribution
- Annual income distribution
- Spending score distribution
- Gender analysis
- Correlation heatmap
- Cluster visualization

These analyses provide insights into customer purchasing behavior and demographics.

---

# Model Evaluation

The predictive model is evaluated using standard machine learning metrics to assess its performance on unseen data.

---

# Technology Stack

## Programming Language

- Python

## Data Processing

- Pandas
- NumPy

## Data Visualization

- Matplotlib
- Seaborn

## Machine Learning

- Scikit-learn

## Algorithms

- Clustering Algorithm
- Classification Model

---

# Project Structure

```text
Customer-Segmentation-and-Retention-Prediction

│
├── Customer_Retention_Prediction.ipynb
├── Mall_Customers.csv
├── requirements.txt
├── README.md
└── images/
```

---

# Key Features

- Customer data preprocessing
- Exploratory Data Analysis (EDA)
- Missing value treatment
- Outlier detection and handling
- Feature encoding
- Feature scaling
- Customer segmentation using clustering
- Predictive machine learning model
- Model evaluation

---

# Business Applications

- Customer Segmentation
- Personalized Marketing
- Customer Relationship Management (CRM)
- Targeted Promotions
- Customer Retention Strategies
- Sales Optimization

---

# Future Improvements

- Compare multiple clustering algorithms (K-Means, DBSCAN, Hierarchical Clustering)
- Hyperparameter tuning for predictive models
- Deploy using Streamlit or Flask
- Build an interactive customer analytics dashboard
- Integrate recommendation systems
- Add explainable AI techniques such as SHAP

---

# Author

**SRISHHA**

# Personalized Nutrition System

## Overview

The Personalized Nutrition System is an end-to-end Data Science and Machine Learning project focused on analyzing dietary habits, nutritional information, and health-related factors to support personalized nutrition recommendations.

The project is organized into two complementary parts:

- **Part 1 – Data Science & Exploratory Data Analysis (EDA):** Data cleaning, preprocessing, integration, and exploratory analysis of dietary and nutritional datasets.
- **Part 2 – Machine Learning:** Development and evaluation of classification models capable of predicting an individual's diet type based on demographic, lifestyle, and health-related characteristics.

Together, these components demonstrate a complete data science workflow, from raw data preparation and exploratory analysis to predictive modeling and performance evaluation.

---

## Project Objectives

- Analyze dietary habits and health-related patterns.
- Explore nutritional characteristics of food products.
- Identify relationships between demographics, lifestyle factors, and diet types.
- Build machine learning models for diet type classification.
- Evaluate model performance and address challenges such as class imbalance.
- Establish a foundation for future personalized nutrition recommendation systems.

---

## Dataset Description

### Dataset 1: Dietary Habits and Health Dataset

This synthetic dataset contains information related to:

- Age
- Gender
- BMI
- Physical Activity Level
- Health Conditions
- Dietary Preferences
- Diet Type

### Dataset 2: Food Nutrition Dataset

This dataset contains nutritional information about food products, including:

- Calories
- Protein
- Carbohydrates
- Fat
- Water Content
- Additional Nutritional Indicators

Both datasets were cleaned, standardized, and prepared for analysis and machine learning applications.

---

## Project Structure

```text
Personalized-Nutrition-System/
│
├── notebooks/
│   ├── Personalized Nutrition System_DS.ipynb
│   └── Personalized Nutrition System_ML.ipynb
│
├── data/
│
├── summary dashboards/
│
└── README.md
```

---

## Part 1 – Data Science & Exploratory Data Analysis

### Key Tasks

- Data Quality Assessment
- Missing Value Handling
- Duplicate Removal
- Category Standardization
- Data Transformation
- Exploratory Data Analysis (EDA)
- Nutritional Data Investigation
- Statistical Summaries and Visualizations

### Key Findings

- Omnivorous diets represent the majority of observations.
- BMI alone is not a strong predictor of diet type.
- Nutritional variables such as calories, fats, carbohydrates, and water content show meaningful relationships.
- Dietary behavior varies across demographic groups and lifestyle factors.
- Data preprocessing significantly improved dataset consistency and usability.

---

## Part 2 – Machine Learning

### Problem Type

**Multi-Class Classification**

### Target Variable

`diet_type`

Classes:

- Omnivorous
- Flexitarian
- Vegetarian
- Vegan
- Pescatarian

### Machine Learning Pipeline

- Feature Engineering
- Label Encoding
- Feature Scaling
- SMOTE Oversampling
- Cross-Validation
- Hyperparameter Optimization

### Models Evaluated

- Random Forest Classifier
- XGBoost Classifier

### Evaluation Metrics

- Accuracy
- Balanced Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### Results

The best-performing models achieved approximately **65% classification accuracy**.

#### Key Observations

- XGBoost achieved slightly higher overall accuracy.
- Random Forest demonstrated competitive balanced performance.
- Severe class imbalance remained the primary challenge.
- Minority diet classes were more difficult to classify accurately.
- Additional balancing strategies and advanced modeling techniques could further improve performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## Business Value

This project demonstrates how Data Science and Machine Learning can be applied to nutrition-related data to:

- Understand dietary behavior patterns
- Support personalized nutrition strategies
- Improve health-focused decision-making
- Build data-driven recommendation systems

---

## Future Improvements

- Nutrition Recommendation Engine Development
- Deep Learning Approaches
- Advanced Feature Engineering
- Enhanced Class Imbalance Handling
- Integration with Real-World Nutrition Datasets

---

## Disclaimer

The datasets used in this project contain synthetic data and are intended solely for educational, research, and portfolio purposes.
````

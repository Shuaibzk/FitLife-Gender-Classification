# FitLife-Gender-Classification

This machine learning project analyzes health and fitness data from the [FitLife dataset](https://www.kaggle.com/datasets/jijagallery/fitlife-health-and-fitness-tracking-dataset) to predict an individual's gender based on various biometric and lifestyle features.

## 📌 Project Objective

To develop and compare classification models (Naive Bayes, Decision Tree, and K-Nearest Neighbors) to predict the target variable `gender` using a real-world health and fitness dataset.

## 🧠 Machine Learning Approach

- Classification Problem
- Models Used:
  - Naive Bayes
  - Decision Tree (Best Performer)
  - K-Nearest Neighbors (KNN)

## 📊 Dataset Description

- Source: [Kaggle - FitLife Dataset](https://www.kaggle.com/datasets/jijagallery/fitlife-health-and-fitness-tracking-dataset)
- Total Records: ~212,839
- Total Features: 21 (plus 1 target label: gender)
- Target Variable: `Gender` (F / M / Other)
- Feature Types:
  - Quantitative: `age`, `bmi`, `height`, `weight`, `calories burned`, etc.
  - Categorical: `activity type`, `smoking status`, `intensity`, etc.

## ⚙️ Preprocessing

- Handled NULL values by deletion/imputation
- Dropped `health_condition` due to many nulls
- Label Encoding for categorical variables
- Feature Scaling using StandardScaler
- Train-Test Split (70:30)

## 📈 Results

| Model          | Accuracy | Precision | Recall |
|----------------|----------|-----------|--------|
| Naive Bayes    | 0.82     | 0.81      | 0.82   |
| K-Nearest Neighbors | 0.93 | 0.93      | 0.93   |
| Decision Tree  | **1.00** | **1.00**  | **1.00** |

✅ **Decision Tree** performed best with perfect accuracy.

## 🧩 Visualizations

- Correlation Heatmap
- Class Distribution (Bar Chart)
- Confusion Matrices

## 🔍 Project Structure


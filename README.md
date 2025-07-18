# 🌫️ AIR QUALITY PREDICTION

Predicting air quality levels using machine learning classifiers trained on PM2.5-based categorized data.

![GitHub last commit](https://img.shields.io/github/last-commit/srikanthpaidakula/AIR-QUALITY-PREDICTION?color=blue)
![Python](https://img.shields.io/badge/Python-100%25-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-orange)

---

## 🧠 Problem Statement

This project aims to **predict air quality levels** using classification machine learning algorithms.

Although the original dataset is a **regression dataset**, PM2.5 values were **categorized into air quality classes** (e.g., Good, Moderate, Unhealthy, etc.) to convert it into a **classification problem**.

---

## 🎯 Approach

- **Target variable**: Air Quality (classified using PM2.5 thresholds)
- **Features used**: `PM2.5`, `Year`, `Month`, `Day`, `Hour`

---

## 🏗️ Project Architecture

1. **Dataset Selection** – Load the air quality dataset.
2. **Data Preprocessing** – Handle missing values and format timestamps.
3. **Feature Engineering** – Extract useful features like hour, month, etc.
4. **Categorization** – Categorize PM2.5 values into air quality labels.
5. **Model Building** – Train 5 classifiers:
   - Decision Tree
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)
6. **Model Evaluation** – Use classification report, accuracy, and cross-validation.
7. **Visualization** – Bar plots, scatter plots for result interpretation.

---

## 🔍 Models Trained

| Model                  | Remarks |
|------------------------|---------|
| ✅ Decision Tree        | Best performer, highly interpretable |
| ✅ SVM                  | Perfect accuracy, computationally heavier |
| ✅ Random Forest        | Strong performance |
| ✅ Logistic Regression  | Good baseline model |
| ✅ KNN                  | Simple, less effective for this data |

---

## 📈 Results & Insights

- **Decision Tree Classifier** showed **perfect accuracy** and excellent performance across all classes. Ideal when **interpretability and simplicity** are key.
- **SVM Classifier** also yielded **perfect accuracy** and excels in **high-dimensional spaces**. A great option if computational resources are not a concern.

### 📋 Evaluation Metrics

- Classification Report
- Accuracy Score
- Cross-Validation Score

---

authors:
  
  - name: Chakilam Samhitha
    affiliation: SR University
    
    - name: Paidakula Srikanth
    affiliation: SR University




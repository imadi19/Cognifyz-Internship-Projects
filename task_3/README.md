# 🍽️ Cuisine Classification – Machine Learning Internship Project

## ✅ Project Overview

This project aims to develop a **machine learning model** that classifies restaurants based on their **primary cuisine type** using structured restaurant data such as location, rating, price range, votes, and more.

The model demonstrates practical application of supervised learning for multi-class classification tasks in the restaurant domain.

---

## 🎯 Objective

- Build a model to classify restaurants based on their primary cuisine type.
- Use features like location, ratings, pricing, and votes.
- Evaluate performance using accuracy, precision, recall, and confusion matrix.

---

## 📊 Dataset

- Contains **9,551 rows and 21 columns** of restaurant data.
- Important Columns:
    - Country Code
    - City
    - Longitude & Latitude
    - Has Table Booking / Online Delivery (binary features)
    - Price Range
    - Aggregate Rating
    - Votes
    - Cuisines (Target Label extracted as Primary Cuisine)

---

## ⚡ Project Steps

1. **Data Preprocessing**
    - Removed rows with missing cuisines.
    - Converted binary columns to numeric (0 or 1).
    - Extracted the first cuisine as the target label.
    - One-hot encoded the 'City' feature.

2. **Model Training**
    - Used a Random Forest Classifier (`n_estimators=100`).
    - 80%-20% train-test split.

3. **Model Evaluation**
    - Calculated Accuracy, Precision, Recall, F1-Score.
    - Visualized Feature Importance.
    - Plotted Confusion Matrix (top 10 most frequent cuisines).

4. **PDF Report Generation**
    - Automatically generated a professional PDF report with results and insights.

---

## 📁 Project Files

- `Dataset.csv` – Original dataset file.
- `Cuisine_Classification.ipynb` – Jupyter Notebook with full code.
- `Task3_Cuisine_Classification_Report.pdf` – Auto-generated project report.
- `generate_report.py` – Python script to generate the PDF report.
- `README.md` – This project documentation.

---

## 📈 Results

- Model achieved approximately **[Insert Accuracy Here]** accuracy.
- Feature importances show Aggregate Rating and Votes as top predictors.
- Confusion Matrix highlights classification strengths and weaknesses.

---

## 🚀 Future Improvements

- Handle class imbalance with SMOTE or class weighting.
- Hyperparameter tuning (GridSearchCV).
- Try advanced models (XGBoost, Neural Networks).
- Deploy as a web application for real-time cuisine prediction.

---

## 👨‍💻 Author

**Aditya Raj**  
Machine Learning Intern at Cognifyz Technologies

---

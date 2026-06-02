# 🚢 Titanic Survival Prediction

Predicting passenger survival on the Titanic using machine learning.

## 📊 Dataset
- 891 passengers, 12 features
- Target: `Survived` (0 = Died, 1 = Survived)

## 🔍 Key Steps
1. Data Cleaning (missing values, outliers)
2. Exploratory Data Analysis (EDA)
3. Feature Engineering (Cabin letters, encoding)
4. Correlation Analysis & Feature Selection
5. Model Training & Comparison

## 🤖 Models Used
- Logistic Regression
- Random Forest
- SVM
- KNN
- Decision Tree
- XGBoost

## 📈 Best Performance
**XGBoost** achieved **83.05% accuracy** and **0.8269 F1-score**

## 📁 Files
- `titanic.ipynb` - Main Jupyter notebook
- `titanic.csv` - Raw dataset
- `requirements.txt` - Dependencies

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook titanic.ipynb

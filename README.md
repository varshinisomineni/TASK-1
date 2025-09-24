# TASK-1
Task 1: Data Cleaning &amp; Preprocessing
# 🚀 AI & ML Internship - Task 1: Data Cleaning & Preprocessing

## 📌 Objective
Learn how to clean and prepare raw data for Machine Learning models.

## 🛠 Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📂 Files in this Repo
- `dataset/titanic.csv` → Raw dataset
- `notebook/data_cleaning.ipynb` → Full code notebook
- `cleaned_titanic.csv` → Final cleaned dataset
- `README.md` → Documentation

## 📊 Steps Performed
1. **Import Dataset & Explore**
   - Loaded Titanic dataset
   - Checked shape, info, and null values

2. **Handle Missing Values**
   - Age → filled with median  
   - Embarked → filled with mode  
   - Cabin → dropped (too many nulls)

3. **Encode Categorical Features**
   - Sex → Label Encoding  
   - Embarked → One-hot Encoding  

4. **Normalize/Standardize Features**
   - Age & Fare standardized (mean=0, std=1)

5. **Detect & Remove Outliers**

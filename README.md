➡️ 🎯 Objectives

- Explore the structure of raw data  
- Identify and handle missing values  
- Encode categorical variables  
- Normalize/standardize numerical features  
- Detect and remove outliers  
- Export a clean dataset for ML tasks

---

➡️ Data-Cleaning-and-Preprocessing
My internship project where I learn to use different libraries of python such as pandas, numpy, Seaborn/Matplotlib

➡️Titanic Dataset Cleaning & Preprocessing 🚢🧼

This project was completed as part of an **AI & ML internship** task focused on **data cleaning and preprocessing**.

The dataset used is a version of the Titanic dataset, and the goal was to clean and prepare the data for use in machine learning models. This includes handling missing values, encoding categorical features, scaling numerical values, and removing outliers.

---



➡️ 🛠️ Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn

---

➡️ 🔧 Cleaning & Preprocessing Steps

1. Data Exploration 
   - Inspected column names, data types, and null values using `.info()` and `.isnull().sum()`

2. Missing Value Handling 
   - Filled missing `Age` values using the median  
   - Filled missing `Embarked` values using the mode  
   - `Cabin` column was not present in the dataset provided

3. Categorical Encoding 
   - Used **Label Encoding** for the `Sex` column  
   - Applied **One-Hot Encoding** to the `Embarked` column using `get_dummies()`

4. Feature Scaling  
   - Standardized `Age` and `Fare` columns using `StandardScaler()` to ensure consistent feature scaling

5. Outlier Detection & Removal 
   - Used boxplots and the **Interquartile Range (IQR)** method to identify and remove outliers in the `Fare` column

6. Exporting Cleaned Data
   - Saved the cleaned dataset to a new file: `Cleaned_Titanic.csv`

---

## ✅ Outcome

The dataset is now **clean, consistent**, and ready to be used in training machine learning models.

---

## 📁 Files Included

- `Titanic-Dataset.csv` – Original dataset  
- `Cleaned_Titanic.csv` – Final cleaned dataset  
- `titanic_cleaning.ipynb` – Jupyter notebook containing all cleaning code

---

➡️ Overview

The Data cleaning requires you to have a good understanding of python programming language and the libraries mentioned above. This helps in completing this task/Project efficiently.



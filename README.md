# 🧹 Data Cleaning & Preprocessing

## 🎯 Objective
Learn how to clean and prepare raw data for machine learning by performing exploratory analysis, handling missing values, encoding categorical variables, scaling features, and removing outliers.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Seaborn / Matplotlib

---

## 📁 Dataset
Dataset: Titanic Dataset  
Download: [Click here to download dataset](https://www.kaggle.com/c/titanic/data)

---

## 📝 Steps Followed

1. **Import Dataset & Explore**
   - View column names, null values, data types.
   - Commands used: `.info()`, `.describe()`, `.isnull().sum()`

2. **Handle Missing Values**
   - Used median to fill missing `Age` values.
   - Used mode to fill missing `Embarked` values.
   - Dropped `Cabin` due to excessive missing data.

3. **Encode Categorical Variables**
   - Converted `Sex` to binary (0 = male, 1 = female).
   - Used `pd.get_dummies()` for `Embarked` column (One-Hot Encoding).

4. **Feature Scaling**
   - Standardized numerical columns like `Age` and `Fare` using `StandardScaler`.

5. **Outlier Detection & Removal**
   - Visualized outliers using `boxplot`.
   - Removed outliers using IQR method.

---


## ✅ Outcome
Prepared a clean, ready-to-model Titanic dataset. This preprocessing pipeline can now be used for classification tasks such as predicting survival.

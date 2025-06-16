# 🛳️ Titanic Dataset - Data Cleaning & Preprocessing

This project is part of an AI & ML internship and focuses on data cleaning and preprocessing using the Titanic dataset. The goal is to prepare raw data for machine learning models by handling missing values, encoding categorical features, scaling numerical features, and removing outliers.

---

## 📁 Dataset

- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `titanic.csv`

---

## 📌 Tasks Performed

### 1. Importing Required Libraries
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `StandardScaler` from `sklearn.preprocessing`

### 2. Exploratory Data Analysis (EDA)
- Checked for missing values and data types.
- Displayed dataset shape and basic statistics.

### 3. Handling Missing Values
- Imputed missing values in:
  - `Age` using median.
  - `Embarked` using mode.

### 4. Encoding Categorical Variables
- Used `LabelEncoder` for `Sex`.
- Applied one-hot encoding for `Embarked`.

### 5. Feature Scaling
- Standardized numerical columns `Age` and `Fare` using `StandardScaler`.

### 6. Outlier Detection and Removal
- Visualized outliers with boxplots.
- Removed outliers in `Fare` using IQR method.

---

## 🛠️ Tools Used

- **Python** (Jupyter Notebook)
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 📊 Final Output

- A clean and preprocessed version of the Titanic dataset.
- Ready for use in ML model building and training.

---

## 📂 Folder Contents

- Main Jupyter Notebook with all code - titanic_cleaned csv file [task1]
- Original dataset - Titanic-Dataset.csv

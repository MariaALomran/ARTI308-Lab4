# ARTI308-Lab4
#  MPG Data Quality Assessment, Preprocessing & PCA

This project analyzes the **Auto MPG** dataset, focusing on data cleaning, preprocessing, feature scaling, and dimensionality reduction using **Principal Component Analysis (PCA)**.

---

## 🎯 Project Objectives

The main goal of this project is to transform raw and partially messy data into a clean format suitable for analysis and machine learning, while exploring relationships between vehicle performance features.

---

## 🔧 Tasks Performed

### 1. Data Quality Assessment
- Loaded the `mpg.csv` dataset.
- Inspected data types, missing values, and summary statistics.
- Identified missing or inconsistent values, especially in the `horsepower` column.

### 2. Handling Missing Values
- Replaced missing or invalid `horsepower` values.
- Converted relevant columns to numeric format.
- Applied imputation using a suitable central value to preserve the dataset.

### 3. Data Cleaning
- Removed unnecessary inconsistencies.
- Ensured numerical features were ready for preprocessing and visualization.
- Prepared the dataset for scaling and PCA.

### 4. Outlier Detection
- Examined numerical variables for unusual values.
- Used boxplots and statistical checks to identify extreme observations.
- Considered outliers during interpretation of results.

### 5. Feature Scaling
- Applied **Min-Max Scaling** to normalize selected features between 0 and 1.
- Applied **Z-score Standardization** to center features around the mean with unit variance.

### 6. PCA & Explained Variance
- Performed **Principal Component Analysis (PCA)** on standardized numerical features.
- Calculated the explained variance ratio for each principal component.
- Used PCA to reduce dimensionality while preserving most of the variation.

### 7. Visualization
- Created a **correlation heatmap** to study relationships between variables.
- Generated a **scree plot** to show explained variance.
- Created a **PCA scatter plot** to visualize the first two principal components.

---

## 📊 Key Insights

- Some vehicle features show strong relationships, such as:
  - **Weight** and **displacement**
  - **Horsepower** and **acceleration / MPG**
- Standardization is essential before PCA because the features are measured on different scales.
- The first few principal components capture most of the dataset’s variation.
- PCA helps summarize the structure of the dataset with fewer dimensions.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📁 Dataset

- `mpg.csv`

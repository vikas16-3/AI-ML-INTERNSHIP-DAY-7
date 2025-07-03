# AI-ML-INTERNSHIP-DAY-7

# 🧠 Task 7: Support Vector Machines (SVM)

## 🎯 Objective
This notebook explores Support Vector Machines (SVMs) for both linear and non-linear classification using the Breast Cancer dataset.

## 📦 Tools and Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

## 📂 Dataset
- *Source*: [Kaggle - Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)
- *Attributes*: 32 columns including diagnosis, mean radius, texture, perimeter, area, smoothness, etc.

## 🛠 Implementation Steps

1. *Environment Setup*
    - Imported libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn.

2. *Data Acquisition*
    - Dataset is automatically downloaded using kagglehub.

3. *Data Preprocessing*
    - Dropped unnecessary columns like id.
    - Converted categorical diagnosis labels into numerical values (M → 1, B → 0).
    - Checked for null values and data types.

4. *Data Visualization*
    - Used seaborn pair plots and heatmaps to analyze feature correlations and distributions.

5. *Model Building*
    - Split data into train and test sets using train_test_split.
    - Applied:
      - *Linear SVM*
      - *Non-linear SVM* (RBF kernel)
    - Performed feature scaling using StandardScaler.

6. *Model Evaluation*
    - Evaluated models using:
      - Accuracy score
      - Confusion matrix
      - Classification report


## 📌 Key Learnings
- SVMs are powerful for classification tasks, especially with high-dimensional data.
- RBF kernel captures non-linear patterns better than a linear kernel.
- Data visualization helps identify separability and feature importance.

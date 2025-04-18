# 🩺 Diagnose Diabetes - Machine Learning Project

This project uses the Pima Indians Diabetes Dataset to build machine learning models that classify whether a person has diabetes or not, based on diagnostic measurements.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results](#results)
- [References](#references)

---

## 📖 About the Project

The goal of this project is to predict diabetes using various clinical features such as glucose level, insulin, BMI, age, and more. Two machine learning models are trained and compared:
- **Logistic Regression**
- **Random Forest Classifier**

Both models are evaluated for performance, and the results are visualized using confusion matrices and classification reports.

---

## 📊 Dataset

- **Name**: Pima Indians Diabetes Dataset  
- **Source**: [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (Target variable)

---

## ⚙️ Methodology

1. **Data Cleaning**:
   - Replacing zeroes in medical fields with `NaN`
   - Filling missing values using the median

2. **Exploratory Data Analysis**:
   - Outcome distribution visualization using Seaborn

3. **Feature Scaling**:
   - Using `StandardScaler` for normalization

4. **Model Training**:
   - Logistic Regression
   - Random Forest Classifier (100 estimators)

5. **Model Evaluation**:
   - Accuracy
   - Confusion Matrix
   - Classification Report

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (sklearn)
- Google Colab

---

## ▶️ How to Run

1. Upload the CSV file in Google Colab.
2. Run the provided code blocks step by step.
3. The models will train and display accuracy, confusion matrices, and performance metrics.

---

## 📈 Results

| Model               | Accuracy  |
|---------------------|-----------|
| Logistic Regression | ~75%+     |
| Random Forest       | ~74%+     |

Both models show good performance, with Random Forest slightly outperforming Logistic Regression.

Confusion matrix heatmaps are also provided for better visual understanding.

---

## 📚 References

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---

## 👤 Author

**Prathvi Raj Chauhan**  
Diagnosing diabetes with the power of machine learning and healthcare data.

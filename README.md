# Diabetes
This project focuses on predicting whether a patient is likely to have diabetes based on medical measurements. Using the **Pima Indians Diabetes Dataset**, we applied data preprocessing, visualization, and classification models to achieve reliable predictions.

# 🧪 Diabetes Prediction Using Machine Learning

This project focuses on predicting whether a patient is likely to have diabetes based on medical measurements. Using the **Pima Indians Diabetes Dataset**, we applied data preprocessing, visualization, and classification models to achieve reliable predictions.

---

## 📊 Dataset

- **Source**: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Rows**: 768 samples
- **Features**: 8 input variables such as:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age

---

## 🔍 Exploratory Data Analysis (EDA)

- Visualized class imbalance between diabetic and non-diabetic cases.
- Handled missing/zero values in features like `Glucose`, `BloodPressure`, `Insulin`, etc.
- Correlation heatmap to identify important features.

---

## ⚙️ Preprocessing

- Replaced 0s in important columns with median values.
- Standardized features using `StandardScaler`.
- Split dataset into training and testing sets.

---

## 🧠 Models Used

| Model        | Accuracy |
|--------------|----------|
| Logistic Regression | ✅ [add your accuracy here] |
| KNN Classifier      | ✅ [add your accuracy here] |
| SVC (Support Vector Machine) | ✅ [add your accuracy here] |

- Evaluated models using **Confusion Matrix**, **Classification Report**, and **Accuracy Score**.
- Chose the best-performing model based on test accuracy.

---

## 📈 Visualizations

- Countplots, histograms, and heatmaps using **Seaborn** and **Matplotlib**.
- Accuracy comparison for different models.

---

## 🧰 Technologies

- Python 🐍
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (sklearn)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   cd diabetes-prediction

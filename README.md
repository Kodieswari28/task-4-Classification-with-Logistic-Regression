# Logistic Regression - Breast Cancer Classification

This project uses Logistic Regression to classify tumors as **benign** or **malignant** using a built-in dataset from Scikit-learn.

---

## 📊 Dataset

- Used `load_breast_cancer()` from `sklearn.datasets`
- 30 features (e.g., radius, texture, area)
- Target: 
  - 0 = Malignant
  - 1 = Benign

---

## ✅ Steps

1. Loaded dataset from sklearn
2. Split data into train and test sets
3. Scaled features using StandardScaler
4. Trained Logistic Regression model
5. Evaluated using:
   - Confusion Matrix
   - Classification Report (Precision, Recall)
   - ROC-AUC Score
6. Plotted ROC Curve
7. Tried different probability threshold (like 0.3)

---

## 📈 Results

- High accuracy
- Good precision and recall
- ROC-AUC ≈ 0.99

---

## 📘 Notes

- Sigmoid function used to predict probabilities
- Threshold > 0.5 → class 1, else class 0



# ❤️ Heart Disease Prediction using Machine Learning

This project predicts the likelihood of heart disease based on medical features using machine learning classifiers. It compares Logistic Regression, Decision Tree, and K-Nearest Neighbors (KNN) to evaluate which model performs best for binary classification.

---

## 📊 Dataset

- **Source**: [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- **Features**:
  - `age`, `sex`, `cp` (chest pain), `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`
- **Target**: `target` — 1 = heart disease, 0 = no disease

---

## 🚀 Models Used

Three classification models were trained and evaluated:

| Model                 | Accuracy | F1 Score |
|----------------------|----------|----------|
| Logistic Regression  | 73.3%    | 0.72     |
| Decision Tree        | 76.7%    | 0.76     |
| K-Nearest Neighbors  | 56.7%    | 0.52     |

- ✅ Decision Tree gave the best performance.
- 📉 KNN underperformed, possibly due to lack of feature scaling.

---

## 🧪 Sample Prediction

An example patient input was tested across all models:

```python
sample_input = [[63, 1, 3, 145, 233, 1, 0, 150, 0, 2.3, 0, 0, 1]]

# Cancer_Detection
# 🧠 Breast Cancer Detection using Machine Learning

This project builds and compares multiple machine learning models to classify tumor types (Benign or Malignant) based on patient diagnostic features.


## 🔍 Objective
To predict whether a tumor is **malignant** or **benign** using diagnostic data, while **maximizing Recall** to reduce false negatives (i.e., avoid missing cancer cases).

## ⚙️ Models Applied
The following supervised models were trained and compared:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**
- **Random Forest Classifier**

Each model was evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **AUC (Area Under the ROC Curve)**

---

## 📈 Best Model Performance

| Metric   | Value |
|----------|-------|
| **Model** | Logistic Regression |
| **Recall** | 0.94 |
| **AUC**    | 0.99 |

These metrics indicate that the best model is highly capable of identifying positive (cancerous) cases and effectively separates the two classes.

---

## ✅ Key Highlights
- Handled outliers using IQR and strategy-based filtering (removal, capping, or keep).
- Feature selection based on correlation threshold.
- Used **GridSearchCV** for hyperparameter tuning (SVM, RF).
- Compared models side-by-side in a performance table.
- Visualized results using **ROC curves** and **confusion matrices**.


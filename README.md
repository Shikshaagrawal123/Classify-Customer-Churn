# Classify-Customer-Churn
This project aims to **predict customer churn** using a machine learning pipeline built in Python. Churn prediction helps businesses proactively engage customers likely to leave, improving retention and long-term profitability.

---

## 📁 Dataset

The dataset used is `5. Classify Customer Churn.csv`. It contains customer information such as:

- Demographics (e.g., gender, senior citizen status)
- Services signed up for (e.g., phone, internet)
- Account details (e.g., tenure, payment method, monthly charges)
- **Target variable**: `Churn` (whether the customer left or stayed)

---

## 🧩 Project Steps

### 🔽 1. Load and Preprocess the Data
- Upload and read CSV file.
- Drop irrelevant ID columns.
- Convert `TotalCharges` to numeric and drop missing values.

### 🔧 2. Encode and Scale
- Label encode all categorical features.
- Split data into training and testing sets (80/20).
- Standardize numerical features using `StandardScaler`.

### 🤖 3. Train Model
- Use a **Random Forest Classifier** to train the model on the scaled features.

### 📊 4. Evaluate Model
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

## ✅ Results

Example output:

```
Accuracy: 0.80+

Confusion Matrix:
[[... ...]
 [... ...]]

Classification Report:
              precision    recall  f1-score   support
           0       0.xx      0.xx      0.xx       xxx
           1       0.xx      0.xx      0.xx       xxx
```

> Note: Metrics may vary depending on dataset versions and random splits.

---

## 📌 Dependencies

Install the following Python libraries before running:

```bash
pip install pandas scikit-learn
```

---

## 🚀 How to Run

1. Clone this repository.
2. Upload your dataset in Colab or your IDE.
3. Run the script step by step to preprocess, train, and evaluate.

---

## 📈 Future Improvements

- Hyperparameter tuning using GridSearchCV.
- Try other classifiers like XGBoost, SVM, etc.
- Feature selection and model explainability (e.g., SHAP values).

---

## 📬 Contact

For questions or collaboration, feel free to reach out!

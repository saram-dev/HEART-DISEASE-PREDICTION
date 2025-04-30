# ❤️ Heart Disease Risk Prediction (Framingham Dataset)

This project uses **Logistic Regression** to predict the 10-year risk of coronary heart disease (CHD) based on medical and lifestyle factors. The data is sourced from the **Framingham Heart Study**, a well-known cardiovascular dataset.

---

## 📁 Dataset

The dataset includes the following features:

- `age` — Age of the patient
- `Sex_male` — Gender (1 = male, 0 = female)
- `cigsPerDay` — Number of cigarettes smoked per day
- `totChol` — Total cholesterol level
- `sysBP` — Systolic blood pressure
- `glucose` — Glucose level
- `TenYearCHD` — Target variable (1 = CHD within 10 years, 0 = no CHD)

---

## 📊 Workflow Summary

1. **Data Preprocessing**
   - Removed irrelevant column: `education`
   - Renamed column `male` to `Sex_male`
   - Handled missing values by dropping null rows
   - Standardized the feature values using `StandardScaler`

2. **Data Visualization**
   - Count plot of heart disease vs no disease
   - Confusion matrix heatmap for model evaluation

3. **Model Building**
   - Used `LogisticRegression` from `scikit-learn`
   - Performed train-test split (70-30)
   - Trained and evaluated the model

4. **Evaluation Metrics**
   - Confusion Matrix
   - Classification Report: Precision, Recall, F1-Score

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Scipy, Statsmodels

---

## 📷 Sample Visualizations

- ✔️ **Countplot** of CHD (heart disease) distribution
- ✔️ **Confusion Matrix Heatmap** to evaluate prediction accuracy

---

## 🚀 How to Run

### 🔧 Prerequisites

Make sure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy statsmodels

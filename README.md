# 🍷 Wine Quality Prediction (Random Forest Classifier)

This project predicts the **quality of wine** using Machine Learning based on various chemical features such as acidity, alcohol percentage, sulphates, pH, density, and more.

### 🎯 Objective
To build a **reliable classification model** that can assist in evaluating wine quality and identifying which chemical properties influence quality the most.

---

## 📂 Dataset Summary
- Total Samples: 1599
- Features: 11 (physicochemical properties)
- Target: Wine Quality (score range)

---

## 🧠 Approach

| Step | Description |
|------|-------------|
| Data Understanding | Performed `df.info()`, `df.describe()` & distribution checks |
| EDA | Visualized correlations, feature relationships, and outliers |
| Preprocessing | Handled scaling, cleaned noise & normalized some features |
| Model Training | Trained **RandomForestClassifier** for robust predictions |
| Evaluation | Used Accuracy, F1-score & Confusion Matrix |

---

## 🧮 Model Performance

| Metric | Score |
|-------|-------|
| Accuracy | (Insert Your Accuracy %) |
| Precision | (Insert Precision) |
| Recall | (Insert Recall) |
| F1 Score | (Insert F1 Score) |

🔍 *You can replace the placeholder values with your actual output.*

---

## 🔥 Key Insights
- **Alcohol** level had the strongest positive impact on wine quality.
- **High volatile acidity** negatively affects taste.
- Random Forest helped reduce overfitting and provided feature importance clarity.

---

## 📊 Visualizations Included
- Heatmap (Correlation)
- Feature Importance Bar Chart
- Distribution Plots
- Pairwise Feature Comparisons


🛠 Tools & Libraries

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-Learn
Google colabs


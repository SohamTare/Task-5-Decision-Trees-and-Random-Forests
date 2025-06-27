# Decision-Trees-and-Random-Forests
Decision Trees and Random Forest



## 🎯 Objective
To implement tree-based models like Decision Tree and Random Forest for classification tasks using the Breast Cancer Wisconsin dataset.

---

## 📂 Dataset
- **Source**: [Breast Cancer Wisconsin Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Target**: `diagnosis` (M = malignant, B = benign)

---

## 🔧 Tools & Libraries
- Python
- scikit-learn
- matplotlib, seaborn
- pandas, numpy

---

## 📌 Steps Implemented

### ✅ 1. Data Preprocessing
- Loaded and cleaned dataset
- Dropped ID and unnamed columns
- Encoded target label (M = 1, B = 0)

### 🌳 2. Decision Tree Classifier
- Trained a basic decision tree with max depth control
- Visualized the tree using `plot_tree`
- Evaluated model using classification report

### 🌲 3. Random Forest Classifier
- Trained with 100 estimators
- Compared performance against Decision Tree
- Used classification metrics for evaluation

### 🔎 4. Feature Importance
- Ranked and visualized top 10 features impacting prediction

### 📈 5. Cross-validation
- Performed 5-fold CV for model validation
- Reported mean accuracy for robustness

---

## 📊 Results

| Model          | Accuracy | Notes                      |
|----------------|----------|----------------------------|
| Decision Tree  | ~92%     | Slightly prone to overfit  |
| Random Forest  | ~96%     | More robust and accurate   |

---

## 🔍 Observations
- Random Forest performs better due to ensembling.
- Feature importance gives insights on which variables drive predictions.
- Tree depth control helps mitigate overfitting in Decision Trees.

---

## 📁 Files
- `decision_tree_random_forest.py`: Main Python script
- `data.csv`: Dataset file (download from Kaggle)
- `README.md`: This file

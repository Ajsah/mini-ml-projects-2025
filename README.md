# Mini Machine Learning Projects (Self-Learning, 2025)

This repo is a small collection of machine learning mini-projects I worked on while practicing end-to-end workflows in Python.

Each project focuses on a different algorithm and includes:

- **Data cleaning**
- **Basic feature engineering**
- **Model training and evaluation**
- **Simple, clear visualizations**

I kept things lightweight and reproducible by using built-in datasets from scikit-learn — no internet connection needed to run them.

---

## Projects

1. **Linear Regression — Diabetes dataset**
   - Predicts disease progression based on 10 medical features
   - Includes EDA, standardization, polynomial features, and learning curve analysis

2. **Logistic Regression — Breast Cancer dataset**
   - Classifies tumors as malignant or benign
   - Includes scaling, ROC/AUC evaluation, and confusion matrix

3. **Decision Tree — Iris dataset**
   - Classifies iris flower species
   - Includes feature importance analysis and 2D decision region plots

---

## How to run

1. **Create and activate a virtual environment**
   ```sh
   python3 -m venv .venv
   source .venv/bin/activate  # macOS/Linux
   # Windows: .venv\Scripts\activate
   ```

2. **Install requirements**
   ```sh
   pip install -r requirements.txt
   ```

3. **Launch notebooks**
   ```sh
   jupyter lab   # or: jupyter notebook
   ```

---

## Folder structure

```
mini-ml-projects-2025/
├── 01_linear_regression_diabetes.ipynb
├── 02_logistic_regression_breast_cancer.ipynb
├── 03_decision_tree_iris.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Key takeaways

- Practiced practical data cleaning and preprocessing
- Tried out feature engineering (polynomial features, scaling, encoding)
- Trained and compared linear regression, logistic regression, and decision tree models
- Created visuals to better understand data, performance, and decision boundaries



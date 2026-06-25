# German Credit Risk Classification

## Project Description

This Machine Learning project focuses on predicting whether a customer represents a **good** or **bad credit risk** using the **German Credit Data** dataset from the UCI Machine Learning Repository.

The project follows a complete Machine Learning workflow, including data exploration, preprocessing, model training, evaluation, comparison, and hyperparameter optimization. Four supervised classification algorithms were implemented and compared to identify the model with the best predictive performance.

---

## Dataset

The project uses the **German Credit Data** dataset available from the UCI Machine Learning Repository.

Dataset characteristics:

- **1,000 customer records**
- **24 predictive features**
- **Binary target variable**
  - Good Credit
  - Bad Credit

The original target values were converted from:

- 1 → Good Credit (0)
- 2 → Bad Credit (1)

to simplify binary classification.

---

## Data Preprocessing

The preprocessing stage includes:

- Data exploration using Pandas
- Statistical summary
- Class distribution visualization
- Train/Test Split (80/20)
- Stratified sampling
- Feature scaling using StandardScaler (inside Pipelines only)
- Data Leakage prevention through Scikit-learn Pipelines

---

## Machine Learning Models

The following classification models were implemented and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

Each model was evaluated using multiple performance metrics rather than relying only on accuracy.

---

## Project Workflow

1. Load the dataset
2. Explore and analyze the data
3. Visualize class distribution
4. Prepare features and target
5. Split training and testing data
6. Train Logistic Regression
7. Evaluate using confusion matrix and ROC curve
8. Compare with Decision Tree, Random Forest, and SVM
9. Optimize models using GridSearchCV
10. Compare optimized models
11. Analyze final results

---

## Author

**Alejandra Bustos**

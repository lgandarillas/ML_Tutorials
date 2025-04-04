# ML_Tutorials

This repository contains my notes for the [Machine Learning](https://aplicaciones.uc3m.es/cpa/generaFicha?est=218&anio=2024&plan=489&asig=15757&idioma=2) course at [UC3M](https://www.uc3m.es/home). It includes tutorials, code snippets, and resources to facilitate learning and implementation of various ML concepts. The code is not entirely my own; it is based on the tutorials provided in class.

#### Setting Up the Environment
To ensure a clean and isolated Python environment, it is recommended to use a virtual environment (`venv`). Follow these steps:
1. Create a virtual environment
```bash
python -m venv venv
```
2. Activate the virtual environment
```bash
source venv/bin/activate
```
3. Install dependencies
```bash
pip install -r requirements.txt
```

---

## Tutorial 1: Work Environment. File Trees
<details>

    - Introduction to file trees and project organization
    - Understanding directory structures
    - Best practices for organizing machine learning projects
</details>

## Tutorial 2: Hyperparameter Optimization (HPO) and Pipelines
<details>

    - Introduction to Hyperparameter Optimization (HPO)
    - Building ML pipelines
    - Automating model tuning with pipelines
</details>

## Tutorial 3: Linear Regression and Hyperparameters
<details>

    - Fundamentals of linear regression
    - Tuning hyperparameters for regression models
    - Best practices for training and evaluation
</details>

## Tutorial 4: Logistic Regression
<details>

    - Introduction to logistic regression
    - Model training and evaluation
    - Handling imbalanced data in classification tasks
</details>

## Tutorial 5: Support Vector Machines (SVM) and Hyperparameter Tuning
<details>

    - Introduction to Support Vector Machines (SVM) as classifiers and regressors
    - Linear SVM: Theory, implementation, and decision boundaries
    - Kernel SVM: Understanding radial basis function (RBF) and its impact
    - Hyperparameter tuning with GridSearchCV and RandomizedSearchCV
    - Optimization techniques: Bayesian Optimization with Optuna
    - Practical applications and visualization of decision boundaries
</details>


## Tutorial 6: Principal Component Analysis (PCA) and Random Forest
<details>

    - Introduction to Principal Component Analysis (PCA)
    - Feature reduction and visualization
    - Random Forest: Theory and implementation
    - Hyperparameter tuning in Random Forest models
</details>

## Tutorial 7: Gradient Boosting (HistGradientBoosting, XGBoost, LightGBM)
<details>

    - Introduction to Gradient Boosting Trees and their core concepts
    - Implementation using `HistGradientBoostingClassifier` from sklearn
    - Handling categorical features and missing values
    - Model evaluation and hyperparameter tuning with RandomizedSearchCV
    - Feature importance via permutation method
    - Using XGBoost: setup, training, and evaluation
    - Using LightGBM: performance comparison and hyperparameter tuning
</details>

## Tutorial 8: Clustering and PCA
<details>

    - KMeans clustering: theory and implementation with sklearn
    - Selecting the number of clusters: Elbow method and Silhouette score
    - Hierarchical clustering: linkage methods and dendrograms
    - DBSCAN: density-based clustering and parameter tuning
    - Principal Component Analysis (PCA) for visualization and preprocessing
    - Clustering analysis using PCA-reduced data
    - Gaussian Mixture Models (GMM) and Expectation-Maximization (EM)
</details>




# 🔍 Feature Selection on Wine Dataset



## 📁 Dataset

The notebook uses the built-in **Wine dataset** from `sklearn.datasets`. It contains 13 numerical features related to wine chemical properties, with a target label representing three types of wine.

---

## 📌 Methods Implemented

### 1. 🔹 Filter Methods

Statistical methods applied independently of any machine learning model:

* **ANOVA F-value (Info Gain)**
* **Chi-Square Test**
* **Correlation Coefficient**
* **Variance Threshold**
* **Mean Absolute Deviation (MAD)**

### 2. 🔸 Wrapper Methods

Model-based iterative feature selection:

* **Forward Selection** using Logistic Regression
* **Backward Elimination** using Logistic Regression
* **Recursive Feature Elimination (RFE)**

### 3. 🔸 Embedded Methods

Feature selection performed as part of model training:

* **Lasso (L1) Regularization**
* **Random Forest Feature Importances**


## 📈 Applications

Understanding feature importance can:

* Improve model accuracy and interpretability
* Reduce overfitting and training time
* Enhance understanding of your dataset

---


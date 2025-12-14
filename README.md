# Wine_Quality_Prediction_ML
This project uses a Random Forest Classifier to predict red wine quality based on physicochemical properties. It includes data preprocessing, exploratory data analysis, correlation visualization, label binarization, model training, evaluation, and a predictive system built in Python.

#  Red Wine Quality Prediction using Machine Learning

##  Project Overview

This project focuses on predicting the **quality of red wine** using Machine Learning techniques. A **Random Forest Classifier** is trained on physicochemical properties of wine to classify it as **Good Quality** or **Bad Quality**. The project demonstrates a complete ML pipeline from data loading to building a predictive system.

---

##  Dataset

* **Name:** Red Wine Quality Dataset
* **Source:** UCI Machine Learning Repository (via Kaggle)
* **Samples:** 1599
* **Features:** 11 physicochemical attributes
* **Target:** `quality`

###  Features Used

* Fixed acidity
* Volatile acidity
* Citric acid
* Residual sugar
* Chlorides
* Free sulfur dioxide
* Total sulfur dioxide
* Density
* pH
* Sulphates
* Alcohol

---

##  Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Project Workflow

1. Importing dependencies
2. Data collection & preprocessing
3. Exploratory Data Analysis (EDA)
4. Correlation analysis using heatmap
5. Label binarization (Good vs Bad wine)
6. Train-test split
7. Model training using Random Forest
8. Model evaluation
9. Building a predictive system

---

##  Label Binarization

* **Good Quality Wine:** Quality ≥ 7 → `1`
* **Bad Quality Wine:** Quality < 7 → `0`

---

##  Model Used

* **Random Forest Classifier**

Random Forest was chosen due to its robustness, ability to handle non-linear data, and reduced risk of overfitting.

---

##  Model Performance

* Evaluated using **Accuracy Score**
* Achieved high accuracy on both training and testing data, indicating good generalization.

---

##  Predictive System

The trained model can take custom wine feature values as input and predict whether the wine is of **Good** or **Bad** quality.

---

##  Key Learnings

* Handling real-world datasets
* Data visualization and correlation analysis
* Feature-target separation
* Classification using ensemble models
* Building end-to-end ML projects

---

##  Author

**Aashish Narayan**

---

 If you found this project useful, don’t forget to star the repository!

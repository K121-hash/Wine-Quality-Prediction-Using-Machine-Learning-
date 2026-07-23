# 🍷 Wine Quality Prediction Using Machine Learning


Machine learning project for predicting wine quality using Random Forest, SGD, and Support Vector Classifier (SVC).


## 📌 Project Overview

This project aims to predict the quality of red wine using machine learning techniques. The dataset contains several physicochemical properties of wine, such as acidity, pH, alcohol content, sulphates, and density.

The goal of this project is to build and evaluate different classification models capable of predicting whether a wine belongs to a high-quality or low-quality category.

Three machine learning algorithms were implemented and compared:

- Random Forest Classifier
- Stochastic Gradient Descent (SGD) Classifier
- Support Vector Classifier (SVC)

---

# 🎯 Project Objectives

The objectives of this project are to:

- Explore and understand the wine quality dataset.
- Clean and preprocess the data.
- Analyze the distribution of wine quality scores.
- Investigate relationships between variables.
- Engineer features for classification.
- Train multiple machine learning models.
- Evaluate model performance using different metrics.
- Identify the most important features influencing wine quality.

---

# 📂 Dataset Information

The dataset used in this project is the **Wine Quality Dataset**.

Dataset characteristics:

- Number of observations: **1,599**
- Number of features: **12**
- Target variable: **quality**
- Dataset type: Classification

### Features

| Feature | Description |
|----------|----------|
| fixed acidity | Fixed acids in wine |
| volatile acidity | Volatile acids in wine |
| citric acid | Amount of citric acid |
| residual sugar | Residual sugar content |
| chlorides | Chloride concentration |
| free sulfur dioxide | Free sulfur dioxide |
| total sulfur dioxide | Total sulfur dioxide |
| density | Density of the wine |
| pH | Acidity level |
| sulphates | Sulphate concentration |
| alcohol | Alcohol percentage |

Target Variable:

- `quality`

For this project, the quality scores were converted into binary labels:

- **0 → Low-quality wine**
- **1 → High-quality wine**

---

# 🛠️ Technologies and Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# 🔄 Project Workflow

The project followed the steps below:

1. Import libraries.
2. Load the dataset.
3. Explore the dataset structure.
4. Perform data cleaning and preprocessing.
5. Analyze class distribution.
6. Discuss class imbalance.
7. Perform exploratory data analysis (EDA).
8. Generate a correlation heatmap.
9. Engineer features.
10. Split the dataset into training and testing sets.
11. Scale numerical features.
12. Train machine learning models.
13. Evaluate model performance.
14. Analyze feature importance.
15. Compare model results.
16. Draw conclusions.

---

# 📊 Exploratory Data Analysis

Exploratory Data Analysis was conducted to understand the structure of the dataset.

The analysis included:

- Distribution plots of all variables.
- Wine quality distribution.
- Correlation heatmap.
- Feature relationship analysis.

Key observations:

- Most wine samples had quality scores of **5** and **6**.
- The dataset showed signs of class imbalance.
- Alcohol and sulphates positively influenced wine quality.
- Volatile acidity negatively affected wine quality.

---

# 🤖 Models Implemented

## 1. Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### Performance

- Accuracy: **89.71%**
- Weighted F1-score: **0.88**

---

## 2. SGD Classifier

The Stochastic Gradient Descent classifier is a linear model optimized using gradient descent.

### Performance

- Accuracy: **85.66%**
- Weighted F1-score: **0.85**

---

## 3. Support Vector Classifier (SVC)

SVC is a supervised machine learning algorithm that separates classes using optimal hyperplanes.

### Performance

- Accuracy: **88.60%**
- Weighted F1-score: **0.87**

---

# 📈 Model Comparison

| Model | Accuracy | Weighted F1-score |
|----------|----------|----------|
| Random Forest | 89.71% | 0.88 |
| SGD Classifier | 85.66% | 0.85 |
| SVC | 88.60% | 0.87 |

### Best Model

The Random Forest Classifier achieved the highest accuracy and overall performance, making it the best model for predicting wine quality.

---

# 🔍 Feature Importance

Feature importance analysis showed that the most influential variables were:

- Alcohol
- Sulphates
- Volatile acidity
- Density
- Citric acid

These variables contributed the most to predicting wine quality.

---

# ✅ Conclusion

This project successfully applied machine learning techniques to predict wine quality based on physicochemical properties.

Three models were trained and evaluated, with the Random Forest Classifier outperforming the other algorithms.

The results demonstrate that machine learning can effectively classify wine quality and identify the key factors that influence wine ratings.

---

# 📁 Repository Structure

```text
wine-quality-prediction/

│── README.md
│── Wine_Quality_Prediction.ipynb
│── winequality.csv
```

---

# 🚀 Future Improvements

Possible improvements for this project include:

- Hyperparameter tuning.
- Cross-validation.
- Handling class imbalance using SMOTE.
- Testing additional models such as XGBoost and Logistic Regression.
- Deploying the model as a web application.

---

# 👩‍💻 Author

**Kyauta Ayuba Dabu**

Data Analyst | Data Scientist | Machine Learning Enthusiast

GitHub:K131-hash
LinkedIn: 

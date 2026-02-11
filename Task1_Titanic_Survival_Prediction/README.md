# Titanic Survival Prediction 🚢

## 📌 Project Overview
This project is part of the CodSoft Data Science Internship.

The objective of this task is to build a Machine Learning model that predicts whether a passenger survived the Titanic disaster based on features like age, gender, ticket class, fare, and family information.

---

## 📊 Dataset Information
The dataset contains passenger details such as:
- PassengerId
- Pclass (Ticket class)
- Sex
- Age
- SibSp (Siblings/Spouses aboard)
- Parch (Parents/Children aboard)
- Fare
- Embarked
- Survived (Target Variable)

---

## 🧹 Data Preprocessing
The following steps were performed:

- Dropped unnecessary columns (PassengerId, Name, Ticket)
- Handled missing values:
  - Age → filled with median
  - Embarked → filled with most frequent value
  - Cabin → dropped due to many missing values
- Encoded categorical variables:
  - Sex → converted to numeric
  - Embarked → one-hot encoding
- Feature Engineering:
  - Created new feature `FamilySize = SibSp + Parch`

---

## 🤖 Model Used
Logistic Regression

Logistic Regression was used because this is a binary classification problem (Survived = 0 or 1).

---

## 📈 Model Performance

Accuracy Achieved: **81%**

### Confusion Matrix:
[[90 15]
[19 55]]


The model performs well in predicting both survivors and non-survivors.

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## 📌 Conclusion
The Logistic Regression model achieved 81% accuracy after proper data cleaning, preprocessing, and feature engineering.

This project demonstrates understanding of:
- Data preprocessing
- Feature engineering
- Model training
- Model evaluation
- Interpretation of confusion matrix

---

### 🔗 Internship
This project is completed as part of the CodSoft Data Science Internship.

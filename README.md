# 🚢 Titanic Survival Prediction with Machine Learning

Predict which passengers survived the Titanic shipwreck using machine learning techniques. This is one of the most iconic beginner projects, combining data cleaning, EDA, feature engineering, and classification models.

---

## 📊 Project Overview

The Titanic dataset is a binary classification problem from Kaggle where the goal is to predict whether a passenger survived based on features like age, class, sex, fare, and more.

🔍 This project includes:
- Full data preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Model building with Logistic Regression
- Evaluation with accuracy score
- Submission generation for Kaggle

---

## 🧱 Tech Stack

- **Python 3**
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for machine learning models
- **Jupyter Notebook** for development

---

## 📁 Folder Structure

Titanic-ML-Project/
│
├── titanic.ipynb # Main notebook with EDA & model
├── train.csv # Training dataset
├── test.csv # Test dataset
├── gender_submission.csv # Sample submission file
├── README.md # Project documentation


---

## 📈 Key Features Explored

- Pclass (Passenger class)
- Sex (Gender)
- Age (Handling missing values)
- SibSp & Parch (Family connections)
- Fare
- Embarked

### 🔧 Feature Engineering:
- Imputed missing values (Age, Embarked)
- Converted 'Sex' and 'Embarked' into numerical format
- Created new family size feature

---

## 🧠 Model Used

- **Logistic Regression**
  - Accuracy: ~78% on test data (subject to tuning)
  - Simplicity and interpretability made it a great first model choice

---


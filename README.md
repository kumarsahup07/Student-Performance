# 🎓 Student Performance Predictor

### Predicting Academic Success with Machine Learning

> *Can we estimate a student's math performance using demographic, educational, and lifestyle factors?*
>
> This project explores that question by combining data analysis, feature engineering, and machine learning to predict student scores with high accuracy.

---

## 🚀 Project Overview

Student performance is influenced by several factors beyond intelligence alone. This project analyzes how variables such as gender, parental education, lunch type, and test preparation affect academic outcomes.

Using a complete Machine Learning pipeline, multiple regression models were trained and evaluated to predict **Math Scores**, achieving an **R² score of ~88%**.

---

## 📊 Dataset Information

The dataset contains information about **1000 students** and includes:

| Feature                     | Description                |
| --------------------------- | -------------------------- |
| Gender                      | Male / Female              |
| Race/Ethnicity              | Student group category     |
| Parental Level of Education | Parent's highest education |
| Lunch                       | Standard or Free/Reduced   |
| Test Preparation Course     | Completed or Not           |
| Reading Score               | Reading marks              |
| Writing Score               | Writing marks              |
| Math Score                  | Target Variable            |

---

## 🎯 Problem Statement

Educational institutions often struggle to identify students who may require additional academic support.

This project aims to:

✅ Understand factors affecting student performance

✅ Discover hidden patterns through data analysis

✅ Build predictive models for math scores

✅ Compare multiple ML algorithms

✅ Select the best-performing model

---

## 🛠️ Tech Stack

### Languages

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* CatBoost

### Machine Learning Algorithms

* Linear Regression
* Ridge Regression
* Lasso Regression
* K-Nearest Neighbors Regressor
* Decision Tree Regressor
* Random Forest Regressor
* AdaBoost Regressor
* XGBoost Regressor
* CatBoost Regressor

---

## 🔍 Exploratory Data Analysis

The project includes a detailed EDA process:

### Data Quality Checks

* Missing Value Detection
* Duplicate Record Verification
* Data Type Validation
* Statistical Summary Analysis

### Visual Analysis

* Gender Distribution
* Race/Ethnicity Distribution
* Lunch Type Analysis
* Test Preparation Impact
* Score Distribution Analysis
* Correlation Insights

### Key Findings

📌 Students completing test preparation courses generally perform better.

📌 Students with standard lunch tend to score higher.

📌 Female students show stronger overall performance in Reading and Writing.

📌 Reading and Writing scores are strong indicators of Math performance.

---

## ⚙️ Feature Engineering

Additional features were created to improve understanding of student performance:

```python
Total Score = Math + Reading + Writing

Average Score = Total Score / 3
```

Categorical variables were transformed using:

* One-Hot Encoding
* Standard Scaling

---

## 🤖 Model Training Pipeline

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
EDA & Visualization
      │
      ▼
Feature Engineering
      │
      ▼
Data Preprocessing
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Best Model Selection
```

---

## 📈 Model Performance

| Model                   | R² Score |
| ----------------------- | -------- |
| Ridge Regression        | 0.880    |
| Linear Regression       | 0.880    |
| CatBoost Regressor      | 0.852    |
| AdaBoost Regressor      | 0.850    |
| Random Forest Regressor | 0.847    |
| Lasso Regression        | 0.825    |
| XGBoost Regressor       | 0.822    |
| KNN Regressor           | 0.784    |
| Decision Tree Regressor | 0.760    |

🏆 **Best Model: Ridge Regression**

---

## 📉 Evaluation Metrics

The following metrics were used:

```python
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
```

---

## 💡 Challenges Faced

### Data Preprocessing

Handling categorical features efficiently before training.

### Feature Selection

Identifying which attributes contribute most to performance prediction.

### Model Comparison

Evaluating multiple algorithms to balance accuracy and generalization.

### Overfitting Prevention

Ensuring models perform well on unseen test data.

---

## 🌟 Future Improvements

* Hyperparameter Tuning
* Feature Importance Dashboard
* Model Deployment using Flask/FastAPI
* Interactive Streamlit Web Application
* Student Performance Recommendation System
* Automated Report Generation

---

## 📂 Project Structure

```text
Student-Performance-Predictor/
│
├── data/
│   └── stud.csv
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── main.py
```

---

## 🏆 Learning Outcomes

Through this project, I gained hands-on experience in:

✔ Data Cleaning

✔ Exploratory Data Analysis

✔ Feature Engineering

✔ Machine Learning Model Development

✔ Regression Analysis

✔ Model Evaluation & Comparison

✔ Data Visualization

---

## 🤝 Connect With Me

If you found this project interesting, feel free to ⭐ the repository and connect with me!

> *"Data tells a story. Machine Learning helps us predict the next chapter."* 🚀

---

### ⭐ If you like this project, give it a star and support the repository!

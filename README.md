## End to End Machine Learning Project
# 🎓Student Performance Prediction

A complete End-to-End Machine Learning project that predicts students' mathematics performance based on demographic and academic features. This project demonstrates the entire ML lifecycle—from data ingestion to model deployment using Flask.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Flask](https://img.shields.io/badge/Flask-Web_App-black?style=for-the-badge&logo=flask)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-purple?style=for-the-badge&logo=pandas)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)

---

## 📌 Project Overview

This project predicts a student's **Math Score** based on various personal and academic attributes such as:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

The project follows a complete Machine Learning pipeline including:

- Data Ingestion
- Data Validation
- Data Transformation
- Model Training
- Model Evaluation
- Model Serialization
- Prediction Pipeline
- Flask Web Application Deployment

---

## 🚀 Features

- End-to-End ML Pipeline
- Modular Project Structure
- Automated Data Preprocessing
- Multiple Regression Models Training
- Hyperparameter Tuning
- Exception Handling & Logging
- Model Serialization using Pickle
- Interactive Flask Web Interface
- Production-ready Folder Structure

---

## 📂 Project Structure

```
mlproject/
│
├── artifacts/
│   ├── model.pkl
│   ├── preprocessor.pkl
│   ├── train.csv
│   ├── test.csv
│   └── data.csv
│
├── notebook/
│   ├── data/
│   ├── 1. EDA STUDENT PERFORMANCE.ipynb
│   └── 2. MODEL TRAINING.ipynb
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── app.py
├── requirements.txt
├── setup.py
└── README.md
```

---

## 📊 Dataset

The dataset contains students' academic and demographic information.

### Features

| Feature | Description |
|----------|-------------|
| Gender | Male/Female |
| Race/Ethnicity | Student Category |
| Parental Education | Parent Qualification |
| Lunch | Standard / Free |
| Test Preparation | Completed / None |
| Reading Score | Reading Marks |
| Writing Score | Writing Marks |

### Target

```
Math Score
```

---

## ⚙️ Machine Learning Workflow

```
Raw Dataset
      │
      ▼
Data Ingestion
      │
      ▼
Train-Test Split
      │
      ▼
Data Transformation
      │
      ▼
Feature Engineering
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Best Model Selection
      │
      ▼
Prediction Pipeline
      │
      ▼
Flask Web Application
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- CatBoost
- XGBoost
- Flask
- HTML
- CSS
- Pickle
- Git
- GitHub

---

## 📈 Models Used

The following regression algorithms were evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor
- XGBoost Regressor
- CatBoost Regressor

The model with the best performance was selected automatically.

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/DebdeepCh/mlproject.git
```

Move into project directory

```bash
cd mlproject
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

---

## 💻 Web Application

Open your browser and visit

```
http://127.0.0.1:5000
```

Enter student information and receive the predicted Math Score instantly.

---


## 👨‍💻 Author

**Debdeep Choudhary**

Mechanical Engineering Undergraduate  
National Institute of Technology Jamshedpur

### Connect with me
- GitHub: https://github.com/DebdeepCh

---

## ⭐ If you found this project helpful

Please consider giving this repository a ⭐ on GitHub.

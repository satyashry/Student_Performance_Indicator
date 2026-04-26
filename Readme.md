# 🎯 Student Exam Performance Predictor

A Machine Learning web application that predicts a student's **Math Score** based on various factors like gender, parental education, lunch type, and test preparation.

---

## 🚀 Live Demo

👉 https://exam-score-predictor-dta5.onrender.com

---

## 📌 Problem Statement

Student performance depends on multiple social and academic factors.
This project aims to **predict math scores** using those features to gain insights and assist in academic improvement.

---

## 🧠 ML Workflow

* Data Collection
* Data Cleaning & Preprocessing
* Feature Engineering
* Model Training & Evaluation
* Model Selection (Best R² Score)
* Deployment using Flask + Render

---

## 🏗️ Project Structure

```
student_performance_indicator/
│
├── app.py
├── requirements.txt
├── Procfile
│
├── artifacts/
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   └── predict_pipeline.py
│   │
│   ├── utils.py
│   ├── logger.py
│   └── exception.py
│
├── templates/
│   ├── index.html
│   └── home.html
│
└── notebook/
```

---

## ⚙️ Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, CatBoost, XGBoost
* **Backend:** Flask
* **Frontend:** HTML, CSS
* **Deployment:** Render
* **Model Serialization:** Dill

---

## 🤖 Models Used

* Linear Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* AdaBoost
* K-Nearest Neighbors
* XGBoost
* CatBoost

👉 Best model selected based on **R² Score**

---

## 📊 Features Used

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score

---

## 🧪 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/student-performance-indicator.git
cd student-performance-indicator
```

### 2. Create virtual environment

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

### 5. Open in browser

```
http://127.0.0.1:5000
```

---

## 🌐 Deployment

This application is deployed on **Render**.

Steps followed:

* Created `requirements.txt`
* Added `Procfile`
* Connected GitHub repo
* Deployed as Web Service

---

## 📈 Future Improvements

* Better UI/UX (modern frontend)
* Add prediction confidence score
* Add visualization dashboard
* Use Deep Learning models
* Add user authentication

---

## 🙌 Author

**  Satyashry **

* GitHub: https://github.com/satyashry
* LinkedIn: https://www.linkedin.com/in/psatyashry24/

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub — it helps!

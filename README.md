# 🩺 Diabetes Prediction using Machine Learning

## 📌 Project Overview
This project is a Machine Learning-based Diabetes Prediction System developed using Python and Scikit-learn. The model predicts whether a patient is diabetic based on important medical parameters such as Age, Blood Pressure, Insulin, Glucose, and Diabetes Pedigree Function.

The application also provides basic health precautions if diabetes is detected.

---

## 🎯 Objective
To build a predictive machine learning model that helps identify diabetes using patient health information.

---

## 📂 Dataset
- Dataset: Diabetes Dataset (diabetes.csv)
- Features Used:
  - Age
  - BloodPressure
  - Insulin
  - Glucose
  - DiabetesPedigreeFunction
- Target Variable:
  - Outcome (0 = No Diabetes, 1 = Diabetes)

---

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- Decision Tree Classifier
- Jupyter Notebook / Google Colab

---

## 📚 Libraries Used

```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score
```

---

## ⚙️ Project Workflow

1. Load the diabetes dataset.
2. Select important features.
3. Split the dataset into training and testing data.
4. Train a Decision Tree Classifier.
5. Evaluate the model using Accuracy Score.
6. Accept patient details from the user.
7. Predict whether the patient has diabetes.
8. Display health precautions if diabetes is detected.

---

## 📊 Machine Learning Algorithm

- Decision Tree Classifier

---

## 📈 Model Evaluation

Evaluation Metric:
- Accuracy Score

Example Output:

```
Model Accuracy: 76.95%
```

*(Accuracy may vary depending on train-test split and random state.)*

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/diabetes-prediction.git
```

2. Navigate to the project folder

```bash
cd diabetes-prediction
```

3. Install required libraries

```bash
pip install pandas scikit-learn
```

4. Run the program

```bash
python diabetes_prediction.py
```

---

## 💻 Sample Input

```
ENTER THE AGE OF PATIENT: 45
ENTER THE BLOODPRESSURE LEVEL OF PATIENT: 80
ENTER THE INSULIN LEVEL OF PATIENT: 130
ENTER THE GLUCOSE LEVEL OF PATIENT: 150
ENTER THE DIABETESPEDIGREEFUNCTION: 0.45
```

---

## 📋 Sample Output

```
Diabetes Detected

Precautions:
1. Avoid sugary foods
2. Exercise daily
3. Drink plenty of water
4. Check sugar levels regularly
5. Consult a doctor
```

---

## 🚀 Future Improvements

- Improve model accuracy using Random Forest and XGBoost.
- Develop a web application using Flask or Streamlit.
- Add data visualization dashboards.
- Perform hyperparameter tuning.
- Deploy the model on the cloud.

---

## 📁 Project Structure

```
Diabetes-Prediction/
│
├── diabetes.csv
├── diabetes_prediction.py
├── README.md
└── requirements.txt
```

---

## 📌 Skills Demonstrated

- Data Preprocessing
- Machine Learning
- Classification
- Decision Tree Algorithm
- Model Evaluation
- Predictive Analytics
- Python Programming
- Data Analysis

---

## 👨‍💻 Author

**Keerthi Mareedu**

Aspiring Data Analyst | Machine Learning Enthusiast

- Python
- SQL
- Power BI
- Machine Learning
- Data Analytics


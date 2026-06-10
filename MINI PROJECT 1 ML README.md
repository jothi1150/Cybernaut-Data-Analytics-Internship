🎓 Student Performance Prediction using Machine Learning
📌 Project Overview

Student Performance Prediction is a Machine Learning project designed to predict students' final grades based on academic and personal factors such as study time, attendance, previous grades, and parental education level.

The objective of this project is to help educational institutions identify students who may require additional academic support and improve overall learning outcomes through data-driven decision-making.

🎯 Problem Statement

Educational institutions often face challenges in identifying students who are at risk of poor academic performance. By leveraging Machine Learning, we can analyze student-related factors and predict final grades in advance, enabling timely intervention and support.

📂 Dataset Information

The dataset contains 500 student records with the following attributes:

Feature	Description

StudyTime	Number of study hours
Attendance	Student attendance percentage
PreviousGrade	Previous academic score
ParentalEducation	Parent education level
FinalGrade	Student final grade (Target Variable)
Dataset Shape
Rows: 500
Columns: 5
Missing Values
No missing values found in the dataset.

🛠️ Technologies Used

Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Scikit-Learn

🤖 Machine Learning Models Used

1. Linear Regression

Used for predicting continuous numerical values.

2. Decision Tree Regressor

Used to model complex relationships between input features and target values.

🔄 Project Workflow
Step 1: Import Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.tree import DecisionTreeRegressor
from sklearn.metrics import mean_squared_error, r2_score

Step 2: Load Dataset
df = pd.read_csv("student_performance.csv")

Step 3: Data Exploration
df.head()
df.info()
df.describe()

Step 4: Check Missing Values
df.isnull().sum()

Step 5: Define Features and Target
X = df[['StudyTime',
        'Attendance',
        'PreviousGrade',
        'ParentalEducation']]
y = df['FinalGrade']

Step 6: Split Dataset
X_train, X_test, y_train, y_test = train_test_split( X, y,test_size=0.2,random_state=42)

Step 7: Train Models

Linear Regression
lr_model = LinearRegression()
lr_model.fit(X_train, y_train)

Decision Tree Regressor

dt_model = DecisionTreeRegressor(random_state=42)
dt_model.fit(X_train, y_train)

Step 8: Evaluate Models

rmse = np.sqrt(mean_squared_error(y_test, y_pred))
r2 = r2_score(y_test, y_pred)

Step 9: Visualization

plt.scatter(y_test, y_pred)
plt.xlabel("Actual Grades")
plt.ylabel("Predicted Grades")
plt.title("Actual vs Predicted Grades")
plt.show()

📊 Results

Linear Regression
Metric	Value
RMSE	2.69
R² Score	0.926
Decision Tree Regressor
Metric	Value
RMSE	4.74
R² Score	0.771
Best Model

✅ Linear Regression achieved better prediction accuracy with an R² Score of 92.6%.

📈 Visualization

The scatter plot compares Actual Grades and Predicted Grades.

A strong positive correlation between actual and predicted values indicates good model performance.

🌍 Real-World Applications

🏫 Schools and Colleges
Predict student academic performance.
Identify students requiring extra support.
📚 Online Learning Platforms
Monitor student progress.
Recommend personalized learning paths.
🎯 Educational Management Systems
Improve student retention rates.
Enable data-driven academic planning.

✨ Benefits
Early identification of struggling students.
Improved academic performance.
Better decision-making for educators.
Personalized student guidance.
Efficient resource allocation.

📚 Learning Outcomes

Through this project, I learned:

Data Preprocessing
Exploratory Data Analysis (EDA)
Feature Selection
Machine Learning Model Training
Model Evaluation (RMSE & R² Score)
Data Visualization
Real-world Educational Analytics

🚀 Future Enhancements
Add more student-related features.
Implement Random Forest Regressor.
Build a web application using Flask.
Deploy the model on cloud platforms.

outputs:

<img width="1920" height="733" alt="Screenshot 2026-06-10 225307" src="https://github.com/user-attachments/assets/f8e28f3c-0e24-4980-83b5-96bdca990f6a" />
<img width="1920" height="461" alt="Screenshot 2026-06-10 225256" src="https://github.com/user-attachments/assets/a7a1413d-8c2f-4d3e-a002-f238e49f1468" />
<img width="1920" height="750" alt="Screenshot 2026-06-10 225244" src="https://github.com/user-attachments/assets/c1242fbe-8341-46b8-a2ac-f4054690ca95" />
<img width="1920" height="724" alt="Screenshot 2026-06-10 225233" src="https://github.com/user-attachments/assets/ccf2c351-78ac-433a-ad78-5836cc733066" />
<img width="1920" height="778" alt="Screenshot 2026-06-10 225223" src="https://github.com/user-attachments/assets/70f7bf56-398a-47cd-9126-8e118fb1f408" />
<img width="1920" height="859" alt="Screenshot 2026-06-10 225211" src="https://github.com/user-attachments/assets/c4610ed8-b5ff-4557-ad57-b4c8a2e6d12b" />


👨‍💻 Author

Jothi

📧 Email: jothi4667@gmail.com

📍 Salem, Tamil Nadu, India

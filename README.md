# Fitness Class Attendance Prediction using Machine Learning

This machine learning project predicts whether a user will attend a fitness class or not, based on various behavioral and demographic features. The goal is to analyze patterns in fitness engagement and build a predictive model using real-world-style data.
The main aim of this project is compare the accuracy score between four different machine learning models.

## 🔍 Objective

To classify fitness class attendance (Yes/No) based on user attributes such as age, gender, past attendance, fitness level, and other relevant factors.

## 📊 Dataset Overview

The dataset includes the following features (customize based on your data):
- booking_id : Unique identifier of the booking.
- months_as_member : The number of months as this fitness club member, minimum 1 month
- weight : The member's weight in kg, rounded to 2 decimal places.
- days_before : The number of days before the class the member registered.
- day_of_week :  The day of the week of the class.
- time : The time of day of the class. Either AM or PM
- category : The category of the fitness class.
- attended : Whether the member attended the class (1) or not (0)

> (Fitness class dataset : https://www.kaggle.com/datasets/ddosad/datacamps-data-science-associate-certification)

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Decision Tree, KNN, Random Forest Classifier, Kmean Clustering, SVC)
- Jupyter Notebook

## ⚙ ML Workflow

1. Load and explore dataset
2. Clean and preprocess data
3. Encode categorical variables
4. Split data into training/testing sets
5. Train and evaluate models
6. Compare performance metrics (accuracy, confusion matrix, etc.)

## ✅ Results

The best-performing model(Random Forest Classifier) achieved an accuracy of '76.66%' on the test set.  
This model helps fitness centers better understand and predict class engagement.

## 📁 How to Run

1. Clone this repository or download the ZIP
2. Open the notebook fitness_class_prediction.ipynb in Jupyter Notebook
3. Run all cells to see data preprocessing, model training, and evaluation

## 👩‍💻 Author

*Priyanka H P*  
Certified Data Analyst | Passionate about fitness & health data  
[LinkedIn](https://www.linkedin.com/in/priyanka-h-p)

# smart-canteen-demand-prediction
A machine learning-based system that predicts daily canteen demand using historical sales data stored in MongoDB. The project integrates data storage, preprocessing, and prediction with visualization.


## Overview

This project predicts daily canteen food demand using Machine Learning.
The dataset is stored in MongoDB and processed using Python to generate predictions and visual insights.

---

## Technologies Used

* Python
* MongoDB
* Pandas
* Scikit-learn
* Matplotlib & Seaborn

---

## Project Workflow

CSV Dataset → MongoDB → Python → Machine Learning Model → Predictions → Graphs

---

##  Features

* Stores dataset in MongoDB database
* Fetches real-time data using PyMongo
* Performs data preprocessing & encoding
* Uses Linear Regression for prediction
* Visualizes results using graphs

---

##  Dataset Columns

* day_of_week
* weather
* exam_period
* previous_sales
* number_of_students
* today_sales

---

## ⚙️ How to Run

### 1️⃣ Start MongoDB

Run:
mongod

### 2️⃣ Import Dataset into MongoDB

mongoimport --db smart_canteen_ml --collection canteen_sales --type csv --headerline --file "smart_canteen_dataset.csv"

### 3️⃣ Run Python Program

python miniproject.py

---

##  Output

* Predicted sales values
* R2 Score & MAE
* Graphs:

  * Actual vs Predicted Sales
  * Sales Distribution
  * Previous vs Today Sales

---

##  Conclusion

This project demonstrates how MongoDB can be integrated with Machine Learning to build a real-world demand prediction system.

---

##  Author

Revathy


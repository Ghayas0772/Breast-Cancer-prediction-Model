# Student Performance Predictor

Predict a student’s race/ethnicity based on their academic scores using **Machine Learning**.

## Project Overview

This project trains a **Random Forest classifier** to predict a student’s `race/ethnicity` from three academic scores:

* Math Score  
* Reading Score  
* Writing Score  

The dataset used is **StudentsPerformance.csv**. The project includes preprocessing, feature scaling, label encoding, and a **Flask web app** for making predictions interactively.

## Folder Structure

* **model/** * `model.pkl` – Trained Random Forest model  
    * `scaler.pkl` – Scaler used for input features  
    * `label_encoder.pkl` – Label encoder for the target variable  
* **templates/** * `index.html` – Flask HTML template for web app  
* `app.py` – Flask application to serve predictions  
* `StudentsPerformance.csv` – Dataset for training and evaluation  
* `StudentPerformance_EDA.ipynb` – Exploratory Data Analysis and preprocessing steps  
* `requirements.txt` – Python dependencies  
* `Dockerfile` – Optional Docker deployment  
* `README.md` – Project documentation  

## How to Run

### 1. Clone Repository

```bash
git clone [https://github.com/Ghayas0772/Student-performance.git](https://github.com/Ghayas0772/Student-performance.git)
cd Student-performance

# Multiple-Disease-Prediction
This repository contains a **Multiple Disease Prediction System** built using **Streamlit**. 
The system utilizes machine learning models to predict the likelihood of various diseases such as **Diabetes** and **Heart Disease** based on user input data.

## Features
- Predict multiple diseases, including **Diabetes** and **Heart Disease**.
- Built using **Streamlit**, providing an interactive and user-friendly web interface.
- Machine learning models, including Logistic Regression, Random Forest, and SVM, for accurate disease prediction.
- Instant predictions based on user input health parameters (e.g., age, BMI, blood pressure).
- Accessible via web browser with **real-time data processing**.

## Technologies Used
- **Python**: Backend language for logic and machine learning models.
- **Streamlit**: Framework for creating the web interface.
- **Scikit-learn**: Library for building and training machine learning models.
- **Pandas** and **NumPy**: For data preprocessing and analysis.
- **Jupyter Notebook**: For model development and experimentation.

## Usage

1. Input your health parameters, such as **age**, **gender**, **BMI**, **blood pressure**, and other related medical data, into the form on the app.
2. Click on the **Predict** button to get the results.
3. The system will display the likelihood of the selected disease based on the input.

## Dataset

The model was trained on publicly available datasets for each disease:
- **Diabetes Dataset**: Diabetes dataset from Kaggle.
- **Heart Disease Dataset**: Heart Disease dataset from Kaggle.

These datasets were pre-processed to ensure data quality and better prediction accuracy.

## Machine Learning Models

The following models have been implemented and evaluated for predictions:
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Each model was tested for accuracy, precision, recall, and other performance metrics to choose the most accurate predictor for each disease.

## Requirements 
- pickle
- streamlit
- streamlit-option-menu

## To Run this project use below command 
- streamlit run "{path}"\multiple disease pred.py

## Results
- Diabetes Prediction 
![Diabetes](https://github.com/user-attachments/assets/ec83f063-e02c-4b2c-89ff-a0d465878df1)

- Heart Disease Prediction 
![Heart Disease](https://github.com/user-attachments/assets/d5a08b80-56fb-4ccf-8790-3a14919baac2)


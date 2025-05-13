# Titanic Survival Prediction 🚢

This project predicts the survival of passengers on the Titanic using machine learning. It's based on the popular Titanic dataset from Kaggle and includes data preprocessing, exploratory data analysis (EDA), and classification model training.

## 📁 Project Structure

📦titanic-survival-prediction
┣ 📜titanic-survival-prediction.ipynb
┗ 📜README.md

## 📊 Dataset

The dataset used in this project is the [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) dataset from Kaggle. It contains data on passengers such as:
- Name
- Sex
- Age
- Ticket class
- Fare
- Number of siblings/spouses aboard
- Port of embarkation
- Survival status (target variable)

## 🔍 Project Workflow

The main steps followed in the notebook are:

1. **Data Loading**  
   Load training and test datasets using pandas.

2. **Exploratory Data Analysis (EDA)**  
   Visualize data to identify patterns, missing values, and feature distributions using `seaborn` and `matplotlib`.

3. **Data Preprocessing**  
   - Handle missing values (e.g., fill or drop)
   - Encode categorical variables
   - Normalize/scale numerical features

4. **Feature Engineering**  
   Derive new features or simplify existing ones to improve model performance.

5. **Model Building**  
   Multiple machine learning models are tested:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)

6. **Evaluation**  
   Evaluate models using metrics such as accuracy, precision, recall, and F1-score.

7. **Prediction**  
   Make final predictions on the test set.
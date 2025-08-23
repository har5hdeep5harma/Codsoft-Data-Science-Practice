# Titanic Survival Prediction Project

## Overview
This project analyzes the famous Titanic dataset to explore the characteristics of passengers who survived or did not survive the disaster. Using machine learning, particularly a Random Forest classifier, the goal is to predict the survival chances of passengers based on various features such as age, sex, passenger class, fare paid, and more.

## Dataset
The dataset contains information about 891 passengers aboard the Titanic, with features including:
- PassengerId
- Survived (target variable: 0 = No, 1 = Yes)
- Pclass (Passenger Class: 1 = 1st, 2 = 2nd, 3 = 3rd)
- Name, Sex, Age
- SibSp (Number of siblings/spouses aboard)
- Parch (Number of parents/children aboard)
- Ticket number
- Fare paid
- Cabin number
- Embarked port (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Structure
- **Titanic-Dataset.csv**: Raw dataset containing passenger data.
- **Titanick.ipynb**: Jupyter Notebook with detailed exploratory data analysis, preprocessing, modeling, and evaluation.
- **README.md**: This file, providing project details and instructions.

## Methodology
1. **Data Exploration**: Investigated missing values, distribution of features, and survival rates.
2. **Preprocessing**: Handled missing data, encoded categorical variables, and dropped irrelevant columns.
3. **Feature Engineering**: Transformed features such as Sex and Embarked for model compatibility.
4. **Modeling**: Trained a Random Forest Classifier to predict survival.
5. **Evaluation**: Assessed model performance via accuracy, precision, recall, F1-score, and confusion matrix.
6. **Feature Importance**: Identified key factors influencing survival predictions.

## Results
- The model achieves a strong predictive performance, with sex, passenger class, and fare being among the most important features.
- The notebook visualizes key insights and model evaluation results for clear understanding.

## How to Run
1. Ensure you have Python 3.8 installed with libraries: pandas, numpy, seaborn, matplotlib, scikit-learn
2. Open `Titanic.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells sequentially to see the full analysis and modeling process.

## Future Work
- Hyperparameter tuning for improved accuracy
- Incorporate advanced feature engineering (e.g., family size, titles)
- Experiment with other classification algorithms

---

Feel free to explore the notebook and modify the code for deeper insights. This project offers a foundational understanding of classification tasks with real-world data.


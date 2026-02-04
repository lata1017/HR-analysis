# HR Analytics: Employee Attrition Prediction

This project focuses on analyzing employee data to understand the factors that lead to attrition (employees leaving the organization). By using machine learning, we aim to predict which employees are likely to leave, helping HR departments improve retention strategies.

## 📌 Project Overview
Losing trained employees is costly for any organization. This project analyzes a dataset containing various employee attributes like job satisfaction, age, years at the company, and salary to build a classification model that predicts employee attrition.

## 🛠️ Tech Stack
* **Language:** Python
* **Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (RandomForestClassifier, Logistic Regression, etc.)

## 📊 Key Highlights
* **Data Cleaning:** Handled categorical variables and checked for data imbalances.
* **Exploratory Data Analysis (EDA):** Identified that factors like 'OverTime', 'JobRole', and 'MonthlyIncome' significantly impact attrition.
* **Modeling:** Evaluated multiple algorithms, with **Random Forest** providing the best balance of accuracy and F1-score.
* **Optimization:** Used Cross-Validation to ensure the model's reliability across different data subsets.

## 📂 Repository Structure
* `HR_Analytics_Attrition.ipynb`: The complete notebook covering EDA, preprocessing, and modeling.
* `HR-Employee-Attrition.csv`: The dataset used for analysis.
* `requirements.txt`: Necessary libraries to run the project.

## 🚀 How to Use
1. Clone the repository to your local machine.
2. Install dependencies: `pip install pandas seaborn scikit-learn`
3. Open the Jupyter Notebook to view the detailed analysis and model performance.

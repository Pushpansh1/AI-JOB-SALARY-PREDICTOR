# AI Job Market Salary Prediction & Analytics

![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC4E20?style=for-the-badge)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/seaborn-5A9BD5?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Joblib](https://img.shields.io/badge/joblib-FFD43B?style=for-the-badge)

An end-to-end **Data Science project** that analyzes the **AI & Data Science job market (2020–2026)** and builds a machine learning system to **predict salaries based on skills, experience, and job attributes**.
---

## Project Overview

The demand for AI and Data Science professionals has grown rapidly across industries. Understanding how **skills, experience, and job characteristics influence compensation** helps both professionals and organizations make better decisions.

This project includes:

- Exploratory Data Analysis of AI job market trends
- Skill demand analysis
- Machine learning models for salary prediction
- Interactive salary prediction web application

---

## Dataset

Dataset: **AI and Data Science Job Market Dataset (2020–2026)**

Key features:

- `job_title`
- `company_size`
- `company_industry`
- `country`
- `remote_type`
- `experience_level`
- `years_experience`
- `education_level`
- `skills_python`
- `skills_sql`
- `skills_ml`
- `skills_deep_learning`
- `skills_cloud`
- `salary`
- `job_posting_month`
- `job_posting_year`
- `hiring_urgency`
- `job_openings`

These variables allow analysis of **salary trends, job demand, and required technical skills**.

---

## Project Workflow

### 1. Data Preprocessing

- Handling missing values
- Removing duplicates
- Feature engineering
- Creating `total_skills`
- Data cleaning

---

### 2. Exploratory Data Analysis (EDA)

Analysis performed:

- Job demand by role
- Salary distribution across job titles
- Skill demand analysis
- Experience vs salary analysis
- Industry hiring trends
- Remote vs onsite jobs

Visualization tools:

- Matplotlib
- Seaborn

---

### 3. Advanced Analysis

- Skill impact on salary
- Job role clustering using **K-Means**
- Dimensionality reduction using **PCA**
- Job market trend analysis

---

### 4. Machine Learning Models

Multiple models were trained and compared:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost
- LightGBM

Evaluation metrics used:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

The best model was selected and saved for deployment.

---

## Machine Learning Pipeline

The ML pipeline includes:

1. Feature preprocessing
2. Numerical scaling
3. Categorical encoding
4. Model training
5. Model evaluation
6. Model saving using `joblib`

---

## Web Application

A web application was developed using **Streamlit**.

The app allows users to input:

- Job title
- Industry
- Experience level
- Education level
- Technical skills
- Company size
- Remote work type

The model then predicts the **expected salary**.

---

## Tech Stack

### Programming Language
- Python

### Data Analysis
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-learn
- XGBoost
- LightGBM

### Web Application
- Streamlit

### Model Storage
- Joblib

---

## Project Structure
AI-Job-Salary-Prediction
├── dataset
│ └── job_market_data.csv
│
├── notebooks
│ └── EDA.ipynb
│ └── Model_Traning.ipynb
│
├── model
│ └── salary_prediction_model.pkl
│
├── app
│ └── app.py
│
├── requirements.txt
└── README.md
The application will launch in your browser.

---

## Example Use Case

A user can input:

- Job Title: Data Scientist
- Experience: 3 Years
- Skills: Python, SQL, Machine Learning
- Education: Master's Degree

The model predicts the **expected salary based on similar job profiles**.

---

## Key Insights

- Python is the most demanded skill in AI roles
- Deep learning skills significantly increase salary
- Experience strongly correlates with salary growth
- Remote AI jobs have increased since 2022
- Larger companies offer higher salaries

---

## Future Improvements

- Deploy the application online
- Add real-time job market data
- Implement model explainability (SHAP)
- Add salary range prediction
- Build a dashboard with market insights

---

## Author

**Pushpansh**

Data Scientist

---

## License

This project is licensed under the MIT License.


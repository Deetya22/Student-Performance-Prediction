# Student Performance Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/Deetya22/Student-Performance-Prediction)

---

## About This Project

I built this project to understand how different academic, personal, and social factors influence students' exam performance using Machine Learning.

Instead of training only one model, I compared three different regression algorithms and evaluated their performance using MAE, RMSE, and R² Score.

This project follows a complete machine learning workflow, from data preprocessing and visualization to model training, evaluation, and model saving.

---

## Objectives

- Explore the Student Performance Factors dataset
- Clean and preprocess the data
- Perform Exploratory Data Analysis (EDA)
- Train multiple machine learning models
- Compare model performance
- Select the best-performing model
- Save the trained model for future use

---

## Dataset

- Source: Kaggle
- Records: 6,607
- Features: 20

Target Variable:

- Exam_Score

Some important features include:

- Hours Studied
- Attendance
- Previous Scores
- Sleep Hours
- Teacher Quality
- Motivation Level
- Tutoring Sessions
- Internet Access
- Family Income
- Physical Activity
- School Type
- Peer Influence

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab
- GitHub

---

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset
- Checked data types
- Handled missing values
- Verified duplicate records
- Encoded categorical variables using Label Encoding
- Prepared feature and target variables

---

## Exploratory Data Analysis

The project includes several visualizations:

- Correlation Heatmap
- Exam Score Distribution
- Hours Studied vs Exam Score
- Attendance vs Exam Score
- Box Plot
- Actual vs Predicted Scores
- Model Comparison

---

## Machine Learning Models

The following regression models were trained and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## Model Performance

| Model | MAE | RMSE | R² Score |
|-------|------:|------:|------:|
| Linear Regression | 1.02 | 2.10 | 0.6888 |
| Random Forest | 1.13 | 2.21 | 0.6546 |
| Decision Tree | 1.73 | 3.30 | 0.2305 |

---

## Best Model

After comparing all three models, Linear Regression achieved the best performance on this dataset.

- MAE: 1.02
- RMSE: 2.10
- R² Score: 0.6888

The trained model was saved using Joblib for future predictions.

---

## Project Structure

```text
Student-Performance-Prediction/
│
├── Student_Performance_Prediction.ipynb
├── StudentPerformanceFactors.csv
├── student_performance_model.pkl
├── README.md
├── requirements.txt
├── LICENSE
├── heatmap.png
├── exam_score_histogram.png
├── hours_vs_exam.png
├── attendance_vs_exam.png
├── boxplot.png
├── actual_vs_predicted.png
└── model_comparison.png
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/Deetya22/Student-Performance-Prediction.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook and run all cells.

---

## What I Learned

Working on this project helped me understand:

- Data preprocessing techniques
- Label Encoding
- Exploratory Data Analysis
- Feature correlation
- Regression algorithms
- Model evaluation using MAE, RMSE and R² Score
- Comparing multiple machine learning models
- Using GitHub to document and share projects

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- XGBoost
- Streamlit web application
- Model deployment

---

## Author

**Tirunagari Deetya Abhirami**

B.Sc. Data Science Student

Learning Machine Learning through hands-on projects.

---

⭐ If you found this project useful, please consider giving it a star.

# 🤖 Week 3 - Day 1: Machine Learning Fundamentals

**Student:** Shaik Arshiya Tabasum  
**Program:** AIML Internship  
**Topic:** Machine Learning Workflow & Linear Regression  

---

## 📌 Assignment Overview

This assignment covers the complete Machine Learning workflow by building a **Student Exam Score Prediction Model** using Linear Regression with the Scikit-learn library.

---

## 📁 Repository Structure

```
week3-day1-ml-fundamentals/
│
├── student_performance.csv     # Dataset (40 student records)
├── assignment.ipynb            # Main Jupyter Notebook
├── ml_workflow.txt             # ML Workflow Documentation
├── answers.txt                 # Research Activity Answers
├── README.md                   # This file
│
└── screenshots/
    ├── actual_vs_predicted.png     # Actual vs Predicted scores chart
    ├── feature_importance.png      # Feature importance bar chart
    ├── residual_plot.png           # Residual error plot
    └── studyhours_vs_score.png     # Study hours vs score scatter plot
```

---

## 📊 Dataset Description

**File:** `student_performance.csv`  
**Records:** 40 students  

| Column | Description |
|--------|-------------|
| StudentID | Unique student identifier |
| StudyHours | Hours studied per day |
| AttendancePercent | Class attendance percentage |
| PreviousScore | Score in previous exam |
| ParentalSupport | Parental support level (0=None, 1=Medium, 2=High) |
| ExamScore | Final exam score (Target Variable) |

---

## 🔧 Technologies Used

- **Python 3**
- **Pandas** — Data manipulation
- **NumPy** — Numerical operations
- **Scikit-learn** — Machine Learning (Linear Regression)
- **Matplotlib** — Data Visualization

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/week3-day1-ml-fundamentals.git
cd week3-day1-ml-fundamentals
```

2. Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib
```

3. Open the notebook:
```bash
jupyter notebook assignment.ipynb
```

---

## 📈 Results

| Metric | Value |
|--------|-------|
| MAE (Mean Absolute Error) | 0.37 |
| R² Score | 0.9995 |

✅ **Excellent model performance!**

---

## 📊 Visualizations

### 1. Actual vs Predicted Scores
![Actual vs Predicted](screenshots/actual_vs_predicted.png)

### 2. Feature Importance
![Feature Importance](screenshots/feature_importance.png)

### 3. Residual Error Plot
![Residuals](screenshots/residual_plot.png)

### 4. Study Hours vs Exam Score
![Study Hours vs Score](screenshots/studyhours_vs_score.png)

---

## 🎯 Key Findings

- 📌 **PreviousScore** and **StudyHours** are the strongest predictors of exam performance
- 📌 Higher study hours directly correlate with better exam scores
- 📌 Parental support has a positive impact on student performance
- 📌 The model achieves R² = 0.9995 — nearly perfect predictions

---

## 📚 Concepts Covered

- ✅ Machine Learning Workflow (10 Steps)
- ✅ Features vs Labels
- ✅ Train-Test Split (80/20)
- ✅ Linear Regression Model
- ✅ Model Evaluation (MAE & R² Score)
- ✅ Predictions on New Data
- ✅ Data Visualization (4 charts)

---

*Made with ❤️ by Shaik Arshiya Tabasum | AIML Internship Week 3*

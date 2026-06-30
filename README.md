# 📊 Predicting Final Exam Scores with Linear Regression

**Author:** Yekta Ansari  
**Date:** June 2026  
**Tools:** Python, pandas, scikit-learn, matplotlib

## 🎯 Project Goal
To predict students' Final exam scores using their Quiz 1 scores.

## 📁 Data
- 29 students
- Features: Quiz 1 score (out of 20)
- Target: Final exam score (out of 20)

## 🔍 Key Questions
1. Can Quiz 1 predict Final scores?
2. What is the relationship between Quiz 1 and Final?
3. How accurate are the predictions?

## 📈 Results
- **Equation:** Final = 3.67+ 0.78 * Quiz_1
- **R² Score:** 0.89 (89% of variation explained)
- **RMSE:** 0.67 points

## 🛠️ How to Run
```bash
# Clone the repository
git clone (https://github.com/Yektaa84/linear-regression-final-score-prediction)

# Install packages
pip install pandas scikit-learn matplotlib numpy

# Run the script
python linear_regression.py

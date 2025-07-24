## Employee Salary Prediction

This project aims to predict whether an individual's salary is above or below $50K based on census data. The analysis is performed using a variety of machine learning models implemented in Python through a Jupyter Notebook.

🧠 Objective

To build a machine learning model that predicts whether a person earns more than \$50K per year based on features like education, occupation, age, gender, etc.

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository – Adult Data Set](https://archive.ics.uci.edu/ml/datasets/adult)
- **Filename**: `adult 3.csv`
- **Features** include:
  - Age
  - Workclass
  - Education
  - Marital-status
  - Occupation
  - Relationship
  - Race
  - Sex
  - Hours-per-week
  - Native-country
  - Income (Target Variable: `<=50K` or `>50K`)

## 🔧 Tools & Libraries

- Python 3.x
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 Process Overview

1. **Data Preprocessing**
   - Handling missing values
   - Label encoding of categorical variables
   - Train-test split

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation heatmap
   - Visual insights using plots

3. **Modeling**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine
   - Model Evaluation with Accuracy, Precision, Recall, F1-score

4. **Conclusion**
   - Comparing model performance
   - Identifying best performing model for salary prediction

## 📈 Results

The best-performing model in terms of accuracy and generalization was GradientBoosting with accuracy 0.8571.

## ✅ How to Run

1. Clone or download this repository.
2. Make sure Python and Jupyter Notebook are installed.
3. Run the notebook:

```bash
jupyter notebook Employee_Salary_Prediction.ipynb
```

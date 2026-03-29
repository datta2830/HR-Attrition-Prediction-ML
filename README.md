# HR-Attrition-Prediction-ML
Machine Learning project to predict employee attrition using classification algorithms.

HR Attrition Prediction using Machine Learning
Overview

Employee attrition is a major concern for organizations. This project uses Machine Learning to predict whether an employee will leave the company based on various factors like job role, salary, work-life balance, and overtime.

Dataset
* Dataset: HR Employee Attrition Dataset
* Contains employee details such as:

  * Age
  * Job Role
  * Salary
  * Job Satisfaction
  * Overtime
  * Work-Life Balance

 Tools & Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* SMOTE (Imbalanced Data Handling)

Project Steps

1. Data Loading and Exploration
2. Data Cleaning (Missing values, duplicates)
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Feature Scaling
6. Train-Test Split
7. Handling Imbalanced Data using SMOTE
8. Model Training:

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * KNN
9. Model Evaluation:

   * Accuracy
   * Precision
   * Recall
   * F1 Score
   * ROC-AUC
10. Hyperparameter Tuning using GridSearchCV

Model Performance

Random Forest performed the best among all models based on F1 Score and overall performance.

Key Insights

* Employees working overtime are more likely to leave
* Low job satisfaction increases attrition
* Work-life balance plays an important role

Business Recommendations

* Reduce overtime workload
* Improve employee satisfaction
* Provide better work-life balance
* Offer competitive salaries

How to Run

1. Clone the repository:
```
git clone https://github.com/your-username/HR-Attrition-Prediction-ML.git
```
2. Open Jupyter Notebook:
```
jupyter notebook
```
3. Run the notebook step by step

Conclusion
This project demonstrates a complete Machine Learning pipeline from data preprocessing to model optimization and business insights.


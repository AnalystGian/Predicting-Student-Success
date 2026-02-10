# Predicting-Student-Success

# Background
Educational institutions collect a wide range of student data, including academic history, attendance, study habits, lifestyle factors, and psychological indicators. Despite having access to this information, many schools rely primarily on historical grades when evaluating student performance and identifying at-risk learners. This limits their ability to intervene early and address non-academic factors that influence learning outcomes.

This project uses student-level data to analyze how academic, behavioral, environmental, and psychological factors contribute to overall academic performance. The goal is to provide clearer visibility into the true drivers of student success and support data-informed academic intervention strategies.

# Project Goal
This project aims to answer the following core questions:
1. Which academic and behavioral factors most strongly influence final exam performance?

2. How does attendance compare to study habits in predicting student success?

3. What role do psychological factors such as motivation and exam anxiety play?

4. Can final exam scores be reliably predicted using pre-exam student data?

5. Which factors are actionable for early academic intervention?

The goal is to transform raw student data into actionable insights that support early identification of at-risk students, targeted academic support, and improved educational outcomes.

# Data Scource
- Dataset: Student Performance Dataset
- Source: Kaggle
- Link: https://www.kaggle.com/datasets/algozee/student/data

# Dataset Overview
- Total Records: 1,000 student records
- Total Features: 18 structured variables

# Scope Limitation
- The analysis focuses on interpretation, insight generation, and regression modeling
- Results are based on a single dataset and may not generalize to all educational contexts

# Key Findings

1. Academic performance is cumulative. Previous academic scores are the strongest predictors of final exam outcomes.

2. Attendance is a high-impact, controllable driver. Students with higher attendance consistently achieve better final scores.

3. Study consistency matters more than intensity. Homework completion and regular study habits show meaningful but variable influence.

4. Exam anxiety is a measurable risk factor. Higher anxiety levels are associated with lower academic performance for a subset of students.

5. Lifestyle factors show limited linear impact in this dataset, likely due to indirect or non-linear effects.

6. Linear regression models perform as well as more complex models, indicating stable, primarily linear relationships between features and outcomes.

# Model Performance Summary
Multiple regression models were evaluated to balance accuracy and interpretability:
- Linear, Ridge, and Lasso regression models achieved similar performance, explaining approximately 90% of the variance in final exam scores.

- Regularization provided only marginal improvements, suggesting low noise and limited overfitting.

- The Random Forest model underperformed relative to linear models, indicating that additional complexity did not improve predictive accuracy.

# Recommendations
- Implement early warning systems using prior academic performance and attendance to identify at-risk students early.
- Prioritize attendance improvement initiatives, as attendance is both impactful and actionable.
- Promote consistent study routines, emphasizing homework completion over last-minute studying.
- Address exam anxiety proactively through mock exams, counseling, and stress-management programs.

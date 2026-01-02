# PHASE 3 PROJECT – STUDENT PERFORMANCE ANALYSIS

## Project Overview

This project aims to analyze student performance data to uncover insights about which factors most influence passing or failing a course. These findings will help educational institutions identify at-risk students early and implement targeted interventions to improve academic outcomes.

## Business Problem

Schools often struggle to identify students at risk of failing before it’s too late. The institution wants to predict which students are likely to pass or fail based on factors like self-study habits, attendance, and class participation. You are responsible for analyzing the data, building predictive models, and translating findings into actionable recommendations that can guide early support programs for struggling students.

## Objectives

1. Identify key factors that predict whether a student will pass or fail.
2. Build baseline and advanced classification models to predict student outcomes.
3. Evaluate models using metrics suitable for imbalanced classes, such as recall, precision, F1-score, and ROC–AUC.
4. Provide actionable recommendations for improving student success rates.

## Methodology
### Data Preparation
- Handled missing values and duplicates (none in this dataset).
- Created a binary target variable pass_fail (1 = pass, 0 = fail).
- Split data into training and test sets.
- Scaled features where necessary for logistic regression.

## Modeling

- Baseline Model: Logistic Regression
- Tuned Model: Logistic Regression with hyperparameter adjustments
- Advanced Model: Random Forest Classifier
- Evaluated models using accuracy, recall, precision, F1-score, and ROC–AUC.

### Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook for analysis
- GitHub for version control and collaboration

## Visualizations & Analysis

- Distribution of self-study hours, attendance, and class participation.
- Correlation heatmap of features with passing outcome.
- ROC curves for Logistic Regression and Random Forest models.
- Feature importance plots to highlight key predictors of passing.

## Recommendations

Based on the analysis:
- Encourage students to maintain consistent weekly self-study hours — the strongest predictor of passing.
- Promote regular class attendance and active participation — supportive factors for academic success.
- Implement early-warning systems using Logistic Regression to identify at-risk students and provide timely interventions.
- Random Forest can be used to predict overall student outcomes, but may miss some failing students, so it is less suited for targeted interventions.

## Conclusion

This project provides data-driven insights into student performance and supports proactive educational strategies. By leveraging predictive modeling, schools can identify at-risk students early, optimize support resources, and ultimately improve overall academic success. The combination of logistic regression and random forest models ensures both targeted and broad predictive capabilities.
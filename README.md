# Data Analysis and ML Pipeline
A complete data analysis and machine learning pipeline to predict student academic performance using real-world educational data.

# Project Overview

This project applies a full machine learning pipeline to predict student performance using various academic and behavioral indicators. It includes data cleaning, visualization, correlation analysis, model training, and evaluation. The goal is to support data-driven decision-making in the education sector.

# Key Features

	•	Cleaned and preprocessed real-world educational data
	•	Visualized trends across gender, subjects, and study behavior
	•	Analyzed correlations between grades, attendance, and self-study
	•	Trained and evaluated a Random Forest classifier
	•	Used multiple evaluation metrics for model assessment
	•	Compared models to choose the best-performing approach

 # Technologies Used
 
	•	Python 3
	•	Pandas – Data wrangling & preprocessing
	•	NumPy – Numerical operations
	•	Matplotlib / Seaborn – Data visualization
	•	Scikit-learn – Machine learning model development & evaluation
	•	Jupyter Notebook – Interactive code development

 # Dataset Description

The dataset contains student details such as:

	•	Academic grades (Math, Physics, Chemistry, etc.)
	•	Weekly self-study hours
	•	Absenteeism records
	•	Participation in extracurricular activities
	•	Gender and other demographic attributes
 
 # Exploratory Data Analysis (EDA)

	•	Data Cleaning:
 
	•	Filled missing values with median
	•	Removed duplicates
	•	Handled outliers using boxplots
 
	•	Descriptive Stats:
 
	•	Calculated averages and distributions
	•	Explored score differences between genders
	•	Visualized study hours vs. performance
 
	•	Correlation Analysis:
 
	•	Strong links between science subjects
	•	Positive correlation with self-study hours
	•	Negative impact of absenteeism on performance
 
 # Model Development
 
	•	Target: Student classified as high or low performer
	•	Features Used:
	•	Study hours
	•	Absences
	•	Grades
	•	Extracurricular participation
	•	Steps:
 
	1.	Label Encoding for categorical data
	2.	Train/Test data split using train_test_split
	3.	Model training with Random Forest Classifier
	4.	Hyperparameter tuning using GridSearchCV

 # Evaluation Metrics
 
	•	Accuracy – Overall prediction correctness
	•	Precision – Correctly predicted positive cases
	•	Recall – True positive rate
	•	F1-Score – Balance between precision and recall
	•	Confusion Matrix – Error analysis
	•	Classification Report – Metric summary

# Results

	•	Model Used: Random Forest Classifier
	•	Performance:
	•	Accuracy: 85%+
	•	High Precision & Recall
	•	Minimal misclassification
	•	Why Random Forest?
	•	Reduces overfitting
	•	Handles imbalance
	•	Noise-resistant
	•	Strong & stable performance vs. Logistic Regression/XGBoost

 



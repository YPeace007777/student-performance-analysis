# Problem Statement
Student Perforamnce Analysis report on the basis on various parameters, Predicting whether the stdent whether the student will pass or fail.

------------------

# Overview 
This project focuses on analyzing student academic performance using Data Science and Machine Learning techniques. The dataset was cleaned, analyzed, visualized, and used to build a predictive model for determining student pass/fail outcomes.

The project demonstrates the complete beginner-level Data Science workflow:

. Data cleaning
. Exploratory data Analysis (EDA)
. Data Visualisation
. Machine Learning
. Model Evaluation

-------------------

# Objectives
. Analyze student performance trends
. Identify factors affecting academic scores
. Visualize relationships between subjects and students attributes
. Predict student pass/fail status using Machine Learning

------------------

# Technologies Used
. Python
. Pandas
. Numpy
. Matplotlib
. Seaborn
. Scikit-learn
. Jupyter Notebook
. Ydata-profiling

------------------

# Dataset
Dataset used:

Studnets Performance in Exams Dataset-
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

The dataset contains:
. Gender
. Race/Ethnicity
. Parental Level of Education
. Lunch Type
. Test Prepration Course
. Math Score
. Reading Score
. Writing Score

-------------------

# Project Workflow 

1. Data Loading
. Imported dataset using Pandas
. Explored dataset structure and dimensions

2. Data Cleaning
. Checked missing values
. Removed duplicate records
. Validated score range
. Standerdized column formatting

3. Exploratory Data analysis (EDA)
Performed analysis on:
. Average student scores 
. Gender-wise performance
. Impact of lunch type
. Effect of test preparation course 

4. Data visualization
Created:
. Histograms
. Boxplots
. Correlation Heatmaps 
. Confusion Matrix

5. Machine Learning
Build a Logistic Regression model to predict:
. Student Pass / Fail outcome

Machine Leanrning Workflow:
. Feature Selection
. Train_Test_Split
. Model Training
. Prediction
. Accuracy evaluation

----------------------

# Machine Learning Model

Model Used:
. Logistic Regression

Features Used:
. Reading Score
. Writing Score

Target Variable
. Pass/Fail based on math score

----------------------

# Model Accuracy
The Logistic Regression model achived approxmately:
97% accuracy

Key Insights:
. Students completing test prepration courses generally scored higher.
. Reading and Writing scores showed strong positive correlation.
. Lunch type appeared to influence academic performance
. <Femeale> studnets performed better on averge in <reading and writing> scores.
. Ethnicity appeared to be also affecting the Results as <Group E> students tend to <perform better> overall.

----------------------

# Visualisations

Correalation Heatmap:
. Shows relationship between subject scores.

Score Distriution Histrogram:
. Displays score frequency distribution.

Gender-wise Boxplot
. Compares academic performance across genders.

Confusion Matrix
. Evaluates machine learning predection performance.

--------------------

# Automated EDA Report

Automated exploratory data analysis was performed using:
. YData Profiling

Generated report includes:
. Feature statistics
. Missing values analysis
. Correlation analysis
. Data quality insights

--------------------

# Future Improvements
. Add Streamlit Web Application
. Use advanced ML algorithms
. Add student grade prediction
. Deploy project online
. Build interactive dashboard 

--------------------

# Learning Outcomes
Through this project, I learned:
. Data processing techniques
. Exploratory data analysis
. Data visualization
. Machine learning basics
. Model evaluation methods 
. Real-world dataset handeling
 
--------------------

# Author
Aman Kumar
AI-DS 2nd year student3
Aspiring Data Science and AI Enthusiast
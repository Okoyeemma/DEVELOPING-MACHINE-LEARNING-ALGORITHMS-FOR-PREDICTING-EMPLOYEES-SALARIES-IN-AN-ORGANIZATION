# DEVELOPING-MACHINE-LEARNING-ALGORITHMS-FOR-PREDICTING-EMPLOYEES-SALARIES-IN-AN-ORGANIZATION

Salary Prediction Using Machine Learning
Overview
This project explores the development and evaluation of machine learning algorithms to predict employee salaries in an organization, using the Dangote Group, Nigeria, as a case study. The study aims to support data-driven decisions in human resource management by creating accurate and reliable salary prediction models.
Dataset
The dataset consists of 1,742 observations with 19 features, including:
•	Demographic Information: Gender, Age, Education Level, etc.
•	Performance Metrics: Performance Score, Projects Handled, Training Hours, etc.
•	Organizational Data: Job Title, Department, Years at Company, etc.
•	Target Variable: Monthly Salary
Objectives
1.	Develop and apply machine learning algorithms to forecast employee salaries based on historical data.
2.	Assess the predictive accuracy of different machine learning models.
3.	Identify key variables influencing employee salaries.
4.	Build a web application to allow real-time salary predictions.
Implemented Models
The following machine learning algorithms were implemented and evaluated:
1.	Decision Tree Regression (DTR)
2.	Elastic Net Regression (ENR)
3.	K-Nearest Neighbors (KNN) Regression
4.	Linear Regression (OLS)
5.	Random Forest Regression (RFR)
6.	Support Vector Machine (SVM) Regression
7.	Gradient Boosting Regression (GBR)
Key Findings
•	Best Models for Deployment: Random Forest Regression (RFR), Decision Tree Regression (DTR), and Gradient Boosting Regression (GBR) were the most accurate but require careful tuning to avoid overfitting.
•	Alternative Model: Support Vector Machine (SVM) also showed competitive performance.
•	Less Suitable Models: Elastic Net Regression (ENR) and Linear Regression (OLS) performed poorly on this dataset.
Web Application
A web-based interface was developed to enable organizations to estimate employee salaries easily and efficiently. The app uses the trained machine learning models and provides predictions in real time.
How to Run the Project
Requirements
•	Python 3.8 or later
•	Required Libraries: pandas, numpy, sklearn, matplotlib, seaborn, flask
Steps
pip install -r requirements.txt  
1.	Run the Jupyter notebook for training and evaluation:
jupyter notebook Salary_Prediction.ipynb  
2.	Launch the web application:
Conclusion
This project demonstrates the potential of machine learning for improving salary prediction accuracy and supporting fair and transparent compensation systems. Future work will focus on further optimizing the models and expanding their application to other domains.
Acknowledgments
This research was conducted using data provided by the Dangote Group, Nigeria.

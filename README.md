 Student Exam Pass Prediction System
(Logistic Regression + Exploratory Data Analysis + Visualization Dashboard)
 Introduction

Student academic performance is influenced by multiple factors such as study hours, attendance rate, past exam scores, parental education, and extracurricular activities. However, manually analyzing these factors to identify whether a student will pass or fail is inefficient and time-consuming.

This project uses Machine Learning (Logistic Regression) along with Exploratory Data Analysis (EDA) and Data Visualization techniques to predict student exam outcomes and understand key influencing factors. The system helps in identifying at-risk students and improving academic performance through data-driven insights.

Problem Statement

Educational institutions generate large amounts of student performance data, but it is difficult to manually analyze and predict student outcomes accurately.

There is a need for an automated system that:

Analyzes student performance data
Identifies patterns affecting success/failure
Predicts whether a student will Pass or Fail
Classifies students into risk categories (High / Medium / Low)

By using machine learning and visualization techniques, this project provides meaningful insights for academic decision-making.

Objectives
To load and preprocess student performance dataset
To perform Exploratory Data Analysis (EDA)
To visualize relationships between academic factors
To clean dataset by handling missing values and duplicates
To encode categorical variables
To analyze student risk categories
To build a Logistic Regression model
To evaluate model performance using classification metrics
To predict student Pass/Fail outcome
Tools and Technologies Used

Programming Language:

Python 

Libraries:

Pandas – Data handling and preprocessing
NumPy – Numerical computations
Matplotlib – Data visualization
Seaborn – Statistical visualization
Scikit-learn – Machine Learning model building

Machine Learning Algorithm:

Logistic Regression
Methodology
Step 1: Data Collection

Student performance dataset is loaded from a CSV file containing academic and behavioral attributes.

Step 2: Data Loading

Dataset is imported using Pandas and basic structure is analyzed.

Step 3: Data Cleaning
Handling missing values
Removing duplicate records
Checking dataset consistency
Step 4: Descriptive Statistics

Basic statistical analysis is performed to understand:

Average study hours
Attendance rate
Past exam scores
Final exam scores
Pass/Fail distribution
Step 5: Exploratory Data Analysis (EDA)

Data visualization is performed using:

Count plots (Pass vs Fail, Gender distribution)
Histograms (Study hours, Attendance, Scores)
Scatter plots (Relationships between variables)
Box plots (Outlier detection)
Step 6: Feature Engineering
Label encoding for categorical variables
Feature selection
Removal of unnecessary columns
Step 7: Risk Analysis

Students are categorized into:

High Risk
Medium Risk
Low Risk

Based on:

Attendance rate
Study hours
Past exam scores
Step 8: Feature Scaling

StandardScaler is used to normalize feature values for better model performance.

Step 9: Model Training

A Logistic Regression model is trained using training dataset.

Step 10: Prediction

The model predicts:

Pass / Fail outcome
Probability of passing
Step 11: Model Evaluation

Model performance is evaluated using:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Confusion Matrix
Step 12: Visualization

Confusion matrix and feature relationships are visualized for better interpretation.

Expected Output

The system provides:

Student Pass/Fail prediction
Risk category classification
Performance visualizations
Model evaluation metrics
Insight into key influencing factors
Applications
Educational institutions
Student performance monitoring systems
Academic counseling support
Early warning system for at-risk students
Data-driven education improvement

📌 Conclusion

This project demonstrates how Machine Learning and Data Analysis can be applied in education to predict student performance. Using Logistic Regression along with EDA and visualization techniques, we can effectively identify students who may need academic support and improve overall learning outcomes.
<img width="714" height="508" alt="Screenshot 2026-06-07 182303" src="https://github.com/user-attachments/assets/4986f9c7-b817-4c72-8426-6006006e1c8e" />
<img width="725" height="508" alt="Screenshot 2026-06-07 182309" src="https://github.com/user-attachments/assets/0fc3db0c-72b0-4b4f-a59f-773c3b830882" />
<img width="706" height="519" alt="Screenshot 2026-06-07 182317" src="https://github.com/user-attachments/assets/d8f30aa7-2aad-4746-a54f-074d9cad4b97" />
<img width="764" height="509" alt="Screenshot 2026-06-07 182325" src="https://github.com/user-attachments/assets/9df06bd4-25ce-45ca-a53b-d06b65be3e8e" />
<img width="765" height="507" alt="Screenshot 2026-06-07 182331" src="https://github.com/user-attachments/assets/55346057-2b8c-41a5-b028-6f63be91e3cb" />
<img width="746" height="524" alt="Screenshot 2026-06-07 182336" src="https://github.com/user-attachments/assets/7318213c-4937-4f1a-bad8-68f8f036e2c4" />
<img width="742" height="509" alt="Screenshot 2026-06-07 182348" src="https://github.com/user-attachments/assets/3b26c1bd-05f3-49bf-8c9d-119f3baece34" />
<img width="712" height="475" alt="Screenshot 2026-06-07 182354" src="https://github.com/user-attachments/assets/f7edcfa4-6ab4-474e-bc67-2322073dabe5" />
<img width="712" height="510" alt="Screenshot 2026-06-07 182401" src="https://github.com/user-attachments/assets/b06c3c80-b93b-4a19-8018-d4d2ec2f855e" />
<img width="1298" height="774" alt="Screenshot 2026-06-07 182425" src="https://github.com/user-attachments/assets/719b99ac-4d16-4b54-b359-8832c3fd375a" />
<img width="737" height="525" alt="Screenshot 2026-06-07 182436" src="https://github.com/user-attachments/assets/0a2aab98-b86d-4aa7-b536-7d73ad0f6ea7" />
<img width="637" height="443" alt="Screenshot 2026-06-07 182446" src="https://github.com/user-attachments/assets/0586c588-5dc0-4e51-92c7-d7e7ab212201" />
<img width="770" height="589" alt="Screenshot 2026-06-07 182452" src="https://github.com/user-attachments/assets/67cb24e2-e32f-4c20-b12e-1bdf7ea32c5d" />




# Breast_Cancer_Prediction
Breast Cancer Prediction Using Machine Learning
This project focuses on predicting breast cancer diagnosis using Machine Learning techniques. The Breast Cancer Wisconsin Dataset is used to classify tumors as Malignant (Cancerous) or Benign (Non-Cancerous) based on various medical features.
The project performs data preprocessing, exploratory data analysis, feature correlation analysis, model training, performance evaluation, and visualization of results. Multiple machine learning algorithms are implemented and compared to determine the most effective model for prediction.
Objectives
Analyze breast cancer data using statistical techniques.
Visualize feature distributions and correlations.
Train and evaluate multiple machine learning models.
Compare model performance using evaluation metrics.
Identify the most important features influencing diagnosis.
Technologies Used
Python
Jupyter Notebook
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Machine Learning Models
The following algorithms were implemented:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Dataset Information
Dataset: Breast Cancer Wisconsin Dataset
Total Samples: 569
Features: 30
Classes:
Malignant (0)
Benign (1)
Project Workflow
Data Loading and Exploration
Data Visualization
Statistical Analysis
Feature Correlation Analysis
Data Preprocessing and Scaling
Model Training
Model Evaluation
Confusion Matrix Analysis
ROC Curve Visualization
Feature Importance Analysis
Results
The trained models achieved high predictive performance.
Model
Accuracy
Linear Regression
95.10%
Decision Tree
94.41%
Random Forest
95.10%
ROC-AUC Scores:
Linear Regression: 0.994
Random Forest: 0.992
Decision Tree: 0.938
Key Findings
Linear Regression and Random Forest achieved the highest accuracy.
ROC-AUC values close to 1 indicate excellent classification performance.
Features such as Worst Perimeter, Worst Concave Points, and Worst Radius were the most influential predictors.
The dataset shows strong separability between malignant and benign tumors.
Conclusion
This project demonstrates the effectiveness of Machine Learning techniques in breast cancer diagnosis prediction. The developed models achieved excellent accuracy and ROC-AUC scores, making them suitable for assisting in medical decision-making. The analysis also highlights the importance of specific tumor characteristics in determining cancer diagnosis.
Project Title: Breast Cancer Prediction Using Machine Learning
Tools: Python, Jupyter Notebook, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

# Predicting Student Placement using Logistic Regression

Project Overview
I built a logistic regression model to predict if a student will be placed based on their CGPA and IQ scores. My goal was to create a straightforward model to understand which factors influence placement and to develop a predictive tool.

**My Process**
I followed these steps for the project:

**Loading and Exploring Data:** I loaded the dataset and checked for missing values and duplicates.

**Selecting Features:** I chose CGPA and IQ as the features for my model.

**Analyzing Data (EDA):** I visualized the relationships between CGPA, IQ, and placement using scatter plots and examined feature distributions with box plots to spot outliers.

**Handling Outliers:** I identified and removed outliers in the 'IQ' data using the Interquartile Range (IQR) method to make my model more robust.

**Splitting Data:** I split the cleaned data into training and testing sets to evaluate my model on new data.

**Scaling Features:** I scaled the CGPA and IQ features using StandardScaler so they contribute equally during training.

**Training the Model:** I trained a Logistic Regression model on my scaled training data.

**Evaluating the Model:** I assessed my model's performance using the accuracy score.

**Visualizing the Decision Boundary:** I visualized the model's decision boundary to see how it separates placed and not placed students.

**Saving the Model:** I saved the trained logistic regression model using pickle so I can use it later or deploy it.

**Dataset**
I used a dataset containing student information, including CGPA, IQ, and placement status.

Dataset: https://drive.google.com/file/d/1wg_mT1vQqMsmgHpf6EklO565QS7RpZ9D/view?usp=sharing

**Results**
My trained logistic regression model achieved an accuracy of [Insert Accuracy Score Here] on the test set. The decision boundary visualization shows how my model distinguishes between placed and not placed students based on their CGPA and IQ.

**Dependencies**

1.pandas

2.numpy

3.scikit-learn

4.matplotlib

5.seaborn

5.mlxtend

6.pickle

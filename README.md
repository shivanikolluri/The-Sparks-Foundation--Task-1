Student Score Prediction Using Supervised Machine Learning
The Sparks Foundation — Graduate Rotational Internship Program
Author: Revathi Sai Shivani Kolluri
Tools: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Algorithm: Linear Regression
Dataset: Hours Studied vs Percentage Score

Project Overview
This project explores the relationship between the number of hours a student studies and their exam score. Using Simple Linear Regression, the goal is to build a predictive model that estimates a student's score based on their study hours.
Key Question: If a student studies for 9.25 hours, what score can they expect?
Answer: The model predicts a score of 93.69% with a Mean Absolute Error of just 4.18.

Project Structure
The-Sparks-Foundation--Task-1/
│
├── Book1.xlsx                        # Dataset: Hours vs Scores
├── Sparks Foundation Task-1.ipynb    # Main Jupyter Notebook
└── README.md

Key Steps
1. Exploratory Data Analysis

Loaded and explored the dataset using Pandas
Analyzed correlation between Hours Studied and Percentage Score
Visualized the relationship using a scatter plot and correlation heatmap

2. Key Finding

There is a strong positive correlation between hours studied and percentage score — the more hours studied, the higher the score.

3. Data Preparation

Split features (Hours) and labels (Scores)
Applied 80/20 train-test split using Scikit-learn

4. Model Training

Trained a Linear Regression model on the training set
Plotted the regression line against actual data points

5. Predictions & Evaluation

Compared Actual vs Predicted scores on the test set
Evaluated model performance using Mean Absolute Error (MAE)


Results
MetricValueAlgorithmLinear RegressionTest Size20%Mean Absolute Error4.18Predicted Score (9.25 hrs)93.69%

Visualizations

Scatter Plot — Hours vs Percentage Score
Correlation Heatmap — relationship strength between variables
Regression Line — fitted model against actual data
Actual vs Predicted — side by side comparison on test data


How to Run
bash# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl jupyter

# Launch Jupyter Notebook
jupyter notebook "Sparks Foundation Task-1.ipynb"

Business Impact
This type of predictive model can help educational institutions:

Identify at-risk students based on study patterns early
Set realistic score expectations for students and counselors
Personalize study recommendations based on target scores


Connect
LinkedIn: linkedin.com/in/shivanikolluri
Email: shivanikolluri04@gmail.com

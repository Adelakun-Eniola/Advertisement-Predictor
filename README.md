### **📈 Advertising Budget & Sales Prediction**

This project applies multiple linear regression to predict product sales based on advertising budgets across three media channels: TV, Radio, and Newspaper. The project was completed using Python, pandas, scikit-learn, and matplotlib.

**🔍 Objective**
To understand how different types of advertising budgets impact sales, and to build a predictive model that estimates sales given future ad budget allocations.

# **📁 Dataset**

The dataset used is from a Kaggle Advertising Dataset, containing the following columns:

TV Ad Budget ($)

Radio Ad Budget ($)

Newspaper Ad Budget ($)

Sales ($) — Target variable

### **✅ Key Steps**

Data Loading & Preparation

Load the CSV dataset.

Check for missing values and clean the data if needed.

Define features (X) and target (y).

Model Training

Use LinearRegression from scikit-learn.

Fit the model to the full dataset.

Output the model intercept and coefficients.

Future Prediction Scenarios

Simulate sales predictions for specific budget allocations where only one channel is used at a time:

$400 on TV

$150 on Radio

$100 on Newspaper

Predict and print expected sales for each scenario.

Visualization

Plot Actual vs. Predicted Sales to visually assess model performance.

Include a perfect prediction line for comparison.


# **📦 Tools Used**

Python

pandas

scikit-learn

matplotlib

🧠 Skills Demonstrated
Exploratory Data Analysis (EDA)

Feature Engineering

Regression Modeling

Visualization & Interpretation

Business-Oriented Scenario Forecasting

💼 How This Project Helps Business Decisions
Budget Allocation: Predict ROI on different ad channels.

Forecasting: Project future sales based on planned ad spend.

Channel Effectiveness: Identify which ad channels drive the most revenue.
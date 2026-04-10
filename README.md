# Customer Purchase Behavior Analysis and Churn Prediction - Data Profiler

## Project Overview
This project focuses on data preprocessing, feature engineering, and exploratory data analysis on a real-world style dataset. The goal is to understand customer purchase behavior and prepare the data for machine learning, specifically for churn prediction.

## Objective
- Clean and preprocess raw data
- Perform exploratory data analysis (EDA)
- Handle multiple data formats (CSV, JSON, SQL, API)
- Identify patterns in customer behavior
- Prepare dataset for machine learning models

## Dataset Description
The dataset contains customer-related information such as:
- Customer ID
- Age
- Gender
- Annual Income
- Purchase Frequency
- Average Order Value
- Total Spending
- Last Purchase (days ago)
- Preferred Channel
- Location
- Churn (Target Variable)

## Project Workflow

### 1. Data Acquisition
- Loaded CSV data using Pandas
- Parsed JSON files
- Connected to SQL database and fetched records
- Retrieved data from API

### 2. Data Understanding and Cleaning
- Used head(), info(), and describe() for exploration
- Identified and handled missing values
- Removed duplicate records
- Corrected data types
- Dropped irrelevant columns

### 3. Exploratory Data Analysis (EDA)
- Univariate analysis (distribution of age, income, purchases)
- Bivariate analysis (gender vs purchases, income vs churn)
- Multivariate analysis (correlation heatmap, feature relationships)

### 4. Data Profiling
- Generated automated profiling report using ydata-profiling
- Analyzed:
  - Missing values
  - Statistical summaries
  - Feature correlations
  - Data quality issues

## Key Insights
- Customers with higher income tend to spend more
- Frequent buyers are less likely to churn
- Customers inactive for a long time have higher churn probability
- Purchase behavior varies across different channels

## Technologies Used
- Python
- Pandas
- Matplotlib
- SQLite
- ydata-profiling

## How to Run the Project

1. Clone the repository
git clone https://github.com/your-username/your-repo-name.git](https://github.com/krinasuthar19/Data-Profiler---Data-Preprocessing

2. Install required libraries
pip install pandas matplotlib ydata-profiling

3. Run Jupyter Notebook
jupyter notebook

4. Open and execute the notebook step by step

## Output
- Cleaned dataset ready for machine learning
- Visualizations for data analysis
- Data profiling report (HTML)

## Future Work
- Feature engineering
- Build machine learning model for churn prediction
- Improve model accuracy
- Deploy model as a web application

## Conclusion
This project demonstrates the complete data analysis pipeline from raw data to insights. It helps in understanding customer behavior and provides a strong base for building predictive models.

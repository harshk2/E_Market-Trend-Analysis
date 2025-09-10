Market-Trend-Analysis
AI-Powered Market Trend Analysis for Amazon Products

This project uses AI and data science techniques to analyze Amazon product data. It provides key insights into market trends, helping to inform business decisions related to inventory, marketing, and product development.

Project Overview

The project focuses on three main objectives:

Sales and Seasonal Trends: Analyzing sales data from 2019 to 2022 to identify overall growth and seasonal patterns.

Product Category Performance: Evaluating which product categories are the most dominant and which show potential for growth based on sales and customer reviews.

Predictive Modeling: Using a time series model (Prophet) to forecast future sales and a regression model (Linear Regression) to analyze factors influencing product pricing.

Methodology
The analysis followed a structured approach:

Data Acquisition: The dataset was obtained from a public Kaggle dataset.

Data Preprocessing: The data was cleaned to handle missing values, duplicates, and outliers. Categorical features were prepared for modeling using one-hot encoding.

Exploratory Data Analysis (EDA): Visualizations were created to explore daily sales trends, category performance, and the relationship between price and reviews.

Modeling:

Prophet: A Prophet model was trained on weekly sales data to forecast future sales and identify yearly seasonality.

Linear Regression: A Linear Regression model was built to predict prices and determine the importance of different product features.

Installation & Setup

Clone the repository:

git clone

Install the required libraries:
pip install pandas matplotlib prophet scikit-learn seaborn kagglehub

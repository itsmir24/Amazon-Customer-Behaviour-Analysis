**Customer Purchase Behavior Analysis for Amazon**
**Overview**
This project analyzes customer purchase behavior on Amazon, one of the largest e-commerce platforms globally. By leveraging customer demographics, product performance data, and transaction details, the analysis aims to provide insights into purchasing trends, customer preferences, and product success. The ultimate goal is to help optimize marketing strategies, enhance product recommendations, and improve the overall customer experience.

Key Features:
Exploratory Data Analysis (EDA): Uncover trends, correlations, and patterns in the data.
Data from multiple sources:
Customer demographics in Excel format.
Product information in CSV.
Transaction details in JSON.
Project Steps
1. Data Collection
Data from three sources are merged using common identifiers such as Customer_ID and Product_ID. The datasets include:

Customer demographics (Excel)
Product information (CSV)
Transaction details (JSON)
Goal: Create a unified dataset for further analysis.

2. Data Cleaning
Missing and incorrect data are addressed:

Numerical columns (e.g., Age, Purchase_Amount) are imputed using median/mode values.
Categorical data (e.g., Customer_Name, Product_Name) is handled through imputation or removal.
Goal: Ensure a clean, complete dataset ready for analysis.

3. Data Transformation
Categorical variables such as Gender and Product_Category are converted to numerical format using one-hot encoding.
Continuous variables like Purchase_Amount and Price are normalized to ensure consistent scaling.
Goal: Prepare data for advanced analysis.

4. Univariate Analysis
Visualizations like histograms and box plots are used to analyze individual features (e.g., Age, Purchase_Amount, Product_Category), focusing on distribution and outliers.

Goal: Understand the spread and distribution of key variables.

5. Bivariate Analysis
Relationships between two variables, such as Age vs. Purchase_Amount or Price vs. Customer_Rating, are examined using scatter plots and correlation matrices.

Goal: Identify correlations affecting purchasing behavior.

6. Multivariate Analysis
Interacting variables (e.g., Discounts, Purchase_Date, Product_Price) are analyzed to understand how multiple factors influence purchasing decisions.

Goal: Understand complex relationships and patterns.

7. Feature Selection
Using statistical methods, only important features like Age, Purchase_Amount, and Product_Category are selected for deeper analysis.

Goal: Focus on key factors driving customer behavior.

8. Visualization
Data is visualized using heatmaps, bar charts, and line graphs to highlight trends such as purchase patterns over time and the impact of discounts.

Goal: Present insights clearly for decision-makers.

9. Conclusion and Reporting
The project concludes with a report of actionable insights, such as:

High-spending customers fall within a specific age group.
Certain product categories perform better in specific regions. Recommendations are provided for optimizing pricing strategies, targeted marketing, and product focus.

Prerequisites
Python: Pandas, NumPy, Matplotlib, Seaborn



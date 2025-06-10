Amazon Products EDA Project
Overview
This project presents an Exploratory Data Analysis (EDA) of Amazon product data, focusing on product ratings, pricing strategies, and category distribution. The analysis explores relationships between discounts, ratings, and pricing to derive actionable insights.

Files
amazon.csv: Raw dataset containing Amazon product information
eda.ipynb: Jupyter notebook with the complete exploratory data analysis
generate_report.py: Python script to generate a PDF report from the EDA findings
EDA_Findings_Report.pdf: Generated PDF report with visualizations and insights
TASK 5 DA.pdf: Original task description
Key Insights
Most products maintain high ratings between 3.5-4.5 stars
Discount percentage doesn't strongly correlate with customer satisfaction
Technology products (computers & accessories) dominate the dataset
Price and rating correlation is minimal, indicating customers value factors beyond price
Some heavily discounted products still receive low ratings
How to Run the Code
Prerequisites
The following Python libraries are required:

pandas
matplotlib
seaborn
reportlab
Install dependencies using:

pip install pandas matplotlib seaborn reportlab
Generate the PDF Report
To generate the PDF report from the EDA findings, run:

python generate_report.py
This will create an EDA_Findings_Report.pdf file containing all visualizations and insights from the analysis.

Report Contents
The generated PDF report includes:

Data summary statistics
Rating distribution analysis
Discount percentage distribution
Discount vs Rating relationship
Actual Price vs Discounted Price analysis
Top product categories
Correlation analysis between numerical variables
Key findings and business insights
Data Cleaning
The script handles the following data cleaning tasks:

Removes currency symbols (₹) and commas from price columns
Converts string values to appropriate numeric types
Extracts main category from the category string
Handles percentage symbols in discount values

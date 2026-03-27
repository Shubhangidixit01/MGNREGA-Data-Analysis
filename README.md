Region-Wise Descriptive Analysis of MGNREGA in India
Project Overview

This project performs a comprehensive descriptive analysis of the Mahatma Gandhi National Rural Employment Guarantee Act (MGNREGA) across Indian states over a seven-year period. The objective is to explore employment generation patterns, wage rate trends, and socio-economic indicators using data preprocessing, exploratory data analysis (EDA), and visualization techniques in Python.

The study aims to identify region-wise variations and long-term trends in employment opportunities provided under MGNREGA and highlight insights that may support policy understanding and socio-economic evaluation.

Objectives

The main objectives of this project are:

To analyze employment generation trends across Indian states under MGNREGA.
To study the variation in average wage rates across different regions.
To examine the average number of employment days provided per household.
To perform region-wise and state-wise descriptive analysis of key socio-economic indicators.
To identify patterns and trends using data visualization and exploratory analysis.
Dataset Description

The dataset used in this project contains MGNREGA related indicators collected across multiple Indian states and districts for seven financial years.

Key Variables in the Dataset
Financial Year
Month
State Code
State Name
District Code
District Name
Approved Labour Budget
Average Wage Rate per Day per Person
Average Days of Employment Provided per Household
Additional employment related indicators

These variables help in understanding employment distribution, wage patterns, and regional development trends.

Technologies and Libraries Used

This project is implemented using Python and several widely used data science libraries.

Programming Language
Python
Libraries
pandas – data manipulation and analysis
numpy – numerical computations
matplotlib – data visualization
seaborn – statistical visualization
Jupyter Notebook – interactive data analysis environment
Project Workflow

The project follows a structured data analysis pipeline.

1. Data Collection

The dataset containing MGNREGA indicators across states and districts is obtained and prepared for analysis.

2. Data Cleaning and Preprocessing

Several preprocessing steps are performed, including:

Handling missing values
Converting data types
Replacing invalid values
Formatting month and year columns
Preparing data for analysis
3. Exploratory Data Analysis (EDA)

EDA is conducted to understand the dataset and extract meaningful insights through:

summary statistics
distribution analysis
trend exploration
correlation analysis
4. Data Visualization

Various visualizations are created to interpret patterns and trends, including:

state-wise employment comparisons
wage rate distributions
time-based employment trends
regional comparisons
5. Insight Generation

The final stage involves interpreting visualizations and summarizing key socio-economic insights derived from the analysis.

Project Structure

The repository follows a structured layout to keep the project organized.

mgnrega-data-analysis
│
├── data
│   ├── raw
│   │   └── original dataset
│   └── processed
│       └── cleaned dataset
│
├── notebooks
│   └── data analysis notebook
│
├── outputs
│   ├── figures
│   └── reports
│
├── scripts
│
├── README.md
└── requirements.txt
Key Analysis Performed

The analysis in this project includes:

Data preprocessing and cleaning
Missing value analysis
State-wise employment generation analysis
Wage rate trend analysis
Region-wise comparison of employment indicators
Visualization of socio-economic trends
Expected Outcomes

The project aims to provide:

A clear understanding of employment trends under MGNREGA
Identification of regional disparities in employment and wages
Insights into long-term patterns in rural employment generation
Visual evidence to support descriptive socio-economic analysis
Future Scope

Further extensions of this project may include:

predictive modeling for employment trends
clustering states based on socio-economic indicators
integrating additional rural development datasets
building an interactive dashboard for visualization
Author

This project is developed as part of a data analysis study focusing on socio-economic trends in India using publicly available MGNREGA data.
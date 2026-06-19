# Mini Project 1 - Multi-Agency Violators Data Analysis
📌 Project Overview

This mini project analyzes the Multi-Agency Violators dataset using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The project focuses on data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization to identify trends in company violations, penalties, and risk scores.

## 🎯 Objectives

- Clean and preprocess the dataset.
- Analyze company violations and penalties.
- Calculate statistical measures using NumPy.
- Explore relationships between variables.
- Create meaningful visualizations.
- Identify high-risk companies and states.


## 📂 Dataset

**Dataset Name:** `multi_agency_violators.csv`

The dataset contains information related to companies with violations reported by multiple government agencies.

### Important Features

- Employer Name
- State
- ZIP Code
- NAICS Description
- OSHA Violations
- OSHA Penalties
- OSHA Fatalities
- EPA Penalties
- MSHA Penalties
- WHD Cases
- Risk Score
- Debarred Status
- Agencies with Violations


## 🛠️ Technologies Used

- Python
- Jupyter Notebook / Google Colab

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- 

## 🧹 Data Cleaning Performed

The following preprocessing steps were completed before analysis:

- Loaded the dataset.
- Checked dataset information.
- Checked missing values.
- Removed duplicate records.
- Filled missing numerical values using the median.
- Verified data types.
- Created a new feature named **Total Penalties**.


# 📊 Analysis Performed

## Pandas

- Display dataset information
- Check missing values
- Remove duplicate rows
- Find Top 10 companies with highest Risk Score
- Calculate average Risk Score by State
- Create Total Penalties column

## NumPy

- Mean OSHA Penalties
- Maximum OSHA Penalties
- Minimum OSHA Penalties
- Median Risk Score
- Standard Deviation of Risk Score

## Matplotlib

- Histogram of Risk Score
- Bar Chart of Top States by Average Risk Score
- Scatter Plot of OSHA Violations vs OSHA Penalties
- Pie Chart of Debarred Companies
- Line Chart of Average Risk Score by State

## Seaborn

- Correlation Heatmap
- Box Plot
- Count Plot
- Pair Plot
- Regression Plot


# 📈 Visualizations

The project includes the following visualizations:

- Histogram
- Bar Chart
- Scatter Plot
- Pie Chart
- Line Chart
- Correlation Heatmap
- Box Plot
- Count Plot
- Pair Plot
- Regression Plot


# 📌 Key Insights

- Some companies have significantly higher risk scores than others.
- Certain states report more company violations.
- OSHA penalties generally increase with higher risk scores.
- Companies violating multiple agencies tend to receive larger penalties.
- Correlation analysis highlights relationships among violations, penalties, and risk scores.


# ▶️ How to Run

1. Clone this repository.

2. Install required libraries.

3. Open the notebook in Jupyter Notebook or Google Colab.

4. Run all cells.

The project generates:

- Data Cleaning Report
- Statistical Summary
- Correlation Analysis
- Risk Score Distribution
- State-wise Analysis
- Multiple Data Visualizations


# 📈 Future Improvements

- Build Machine Learning models for Risk Prediction.
- Create an interactive dashboard using Power BI or Tableau.
- Perform advanced statistical analysis.
- Deploy the project as a web application.

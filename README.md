# 🏢 Building Energy Consumption Prediction
### Data Mining | Multiple Linear Regression | Mini-Project

## 📌 Project Overview

This project focuses on analyzing and predicting building energy consumption using Multiple Linear Regression. Using building characteristics, environmental conditions, occupancy levels, geographical information, and maintenance history, the project explores the factors influencing energy usage and develops a predictive model to estimate energy consumption.

The objective is to demonstrate how data mining and machine learning techniques can support data-driven energy management and consumption estimation.

## 🎯 Project Objectives

- Explore building-level energy consumption patterns.
- Identify relationships between building characteristics and energy usage.
- Clean and preprocess raw data for machine learning.
- Investigate correlations and potential multicollinearity between independent variables.
- Develop a Multiple Linear Regression model to predict energy consumption.
- Evaluate model performance using statistical metrics.
- Investigate the impact of outlier detection and removal on model performance.

## 📂 Dataset Description

The project uses the `energy_data.csv` dataset, containing building-level energy readings and contextual attributes.

Key features include:

| Feature | Description |
|---|---|
| Building_Type | Primary building usage category |
| Governorate | Geographical location |
| Neighborhood | District or local area |
| Day_of_Week | Day of recorded measurement |
| Occupancy_Level | Low, Medium, or High |
| Appliances_Usage_Level | Appliance usage intensity |
| SquareFootage | Total building floor area |
| Average_Temperature | Average ambient temperature |
| Last_Maintenance_Date | Date of last maintenance |
| Energy_Consumption | Target variable |

## ⚙️ Methodology

### 1. Data Inspection & Cleaning
- Inspected dataset dimensions, data types, and missing values.
- Standardized categorical text values.
- Removed unnecessary characters from numerical columns.
- Converted columns into appropriate data types.
- Handled missing numerical values using median imputation.
- Handled missing categorical values using mode imputation.

### 2. Feature Engineering
- Created `Days_Since_Last_Maintenance` from the last maintenance date.
- Derived `Day_type` to distinguish weekdays from weekends.
- Prepared numerical and categorical features for modeling.

### 3. Exploratory Data Analysis (EDA)
- Analyzed neighborhood distributions.
- Examined energy consumption across building types.
- Investigated relationships between numerical variables and energy consumption.
- Explored numerical distributions and potential outliers.
- Used correlation analysis to investigate multicollinearity.

### 4. Data Preparation
- Applied One-Hot Encoding to nominal categorical variables.
- Applied Label Encoding to ordinal variables.
- Removed irrelevant identifiers and redundant date columns.
- Split the dataset into training and testing subsets (80:20).

### 5. Model Development
Implemented a Multiple Linear Regression model using Scikit-learn to estimate building energy consumption based on the prepared independent variables.

### 6. Model Evaluation
Evaluated predictive performance using:

- **R² Score:** Measures how well the model explains the variance in energy consumption.
- **Root Mean Squared Error (RMSE):** Measures the magnitude of prediction errors.

### 7. Outlier Analysis
- Detected potential outliers using boxplots.
- Applied the Interquartile Range (IQR) method to identify outliers in average temperature.
- Investigated the potential impact of outlier removal on model performance.

## 📊 Technologies & Tools

| Technology | Application |
|---|---|
| Python | Programming and analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning and model evaluation |
| Jupyter Notebook | Development environment |

## 📈 Key Deliverables

- Data cleaning and preprocessing workflow.
- Exploratory data analysis and statistical visualizations.
- Feature engineering and categorical encoding.
- Multiple Linear Regression predictive model.
- Model evaluation using R² and RMSE.
- Outlier detection and performance investigation.

## 💡 Business Applications

The project demonstrates how predictive analytics can support:

- Building energy consumption estimation.
- Energy management and resource planning.
- Identification of factors influencing energy demand.
- Data-driven operational decision-making.
- More informed energy efficiency initiatives.

---

**Project Category:** Data Mining | Machine Learning | Predictive Analytics

**Model:** Multiple Linear Regression

**Dataset:** Energy Consumption Dataset

# NHANES Analysis: Effects of Physical Activity and BMI on Blood Pressure

This project investigates how **Body Mass Index (BMI)** and **physical activity** relate to **systolic and diastolic blood pressure** using **NHANES** survey data. The goal is to quantify these relationships using statistical modeling and provide clear, reproducible analysis for health-focused insights.

## Project Overview
- **Dataset:** NHANES (U.S. National Health and Nutrition Examination Survey)
- **Focus:** Blood pressure outcomes (SBP/DBP) in relation to BMI and physical activity
- **Approach:** Cleaning + EDA + regression modeling + interpretation

## Key Questions
1. How strongly is **BMI** associated with systolic blood pressure?
2. Does **physical activity** relate to blood pressure after controlling for BMI and demographics?
3. Do relationships change by **age** (interaction effects)?

## Methods
- Data preparation (filtering, recoding categorical variables, handling missingness)
- Descriptive statistics (Table 1 style summary)
- Exploratory Data Analysis (distribution checks, group comparisons)
- Regression modeling:
  - Baseline multiple regression
  - Interaction modeling (e.g., **BMI × Age**)
- Diagnostic checks (residual patterns, model fit)

## Repository Structure (Suggested)


## How to Run (Customize to your setup)
### Option A: R (Recommended if your analysis is in R)
1. Install required packages:
   ```r
   install.packages(c("tidyverse", "broom", "ggplot2", "readr", "dplyr"))
python -m venv venv
source venv/bin/activate  # Mac/Linux
# venv\Scripts\activate   # Windows
pip install -r requirements.txt
jupyter notebook


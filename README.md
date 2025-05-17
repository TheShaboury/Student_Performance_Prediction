# Student Performance Prediction Project

Predicting student exam scores based on lifestyle and study habits using machine learning.

## Project Overview

This project analyzes factors influencing student academic performance and develops predictive models to estimate exam scores.
The best model (Ridge Regression) achieved 90% accuracy (R²=0.90) in predicting exam scores.

**Key Findings:**
- Study hours, sleep duration, and attendance are most predictive of exam scores
- Optimal study time is 6-8 hours daily
- 8+ hours of sleep significantly improves performance
- Balanced extracurricular activities (3-5 hours weekly) correlate with better outcomes

## Requirements
- numpy==1.21.5
- pandas==1.4.2
- matplotlib==3.5.1
- seaborn==0.11.2
- scikit-learn==1.0.2
- jupyter==1.0.0
- ipython==8.2.0
- joblib==1.1.0

## Data

The dataset contains records from 1,000 students including:

- Academic performance metrics
- Study habits (hours spent studying, attendance)
- Lifestyle factors (sleep duration, extracurricular activities)
- Demographic information

## Key Results

Model	               R²Score	  RMSE

Linear Regression	   0.90	      5.14

Ridge Regression	   0.90	      5.14

Lasso Regression	   0.87	      6.02

Random Forest	       0.89	      5.43

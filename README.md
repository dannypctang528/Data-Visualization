# Data-Visualization
Create Word Clouds and Waffle Chart
🇨🇦 Canada Statistics Demo — NPower JDA Course (Module 3)

Overview
  This project demonstrates how to visualize and analyze Canadian job market data using Python.
  It was created as part of NPower Canada’s Junior Data Analyst (JDA) Course — Module 3: Data Visualization with Python.

  The project focuses on:
    - Creating Word Clouds for job titles across provinces
    - Building Waffle Charts to show job type distribution
    - Using statistical and regression analysis to find insights from the data


Objectives
After completing this project, learners will be able to:
  1. Load and clean real-world CSV data using Pandas
  2. Generate Word Clouds for text visualization
  3. Create Waffle Charts for categorical proportions
  4. Apply interactive elements using ipywidgets
  5. Discover insights using correlation, scatter, and regression plots


Dataset Information
File: Canada Statistic Demo.csv
Description: Synthetic dataset simulating job market statistics across 10 Canadian provinces.
Column Name               | Description
Province                  | Province name
Company_Name	            | Employer or organization name
Job_Title                 |	Job position title
Job_Type	                | Category (e.g. IT, Food, Construction)
Company_Size	            | Company scale (Low, Medium, High)
Vacancies	                | Number of job openings
Company_Revenue_Million	  | Annual revenue in millions
Remote_Friendly	          | Whether remote work is available
Avg_Salary	              | Average salary (CAD)


Libraries Used
  pandas, numpy, matplotlib, seaborn, wordcloud, pywaffle, ipywidgets, IPython, scipy...etc


Project Flow
  1️. Import & verify dataset
  2️. Data preprocessing and cleaning
  3. Part 1: Create Word Clouds (All provinces + by province)
  4. Part 2: Create Waffle Charts (All provinces + dropdown interaction)
  5. Part 3: Analyze correlations and regression insights
  6. Discussion & findings


Sample Visuals
  1. Word Cloud: Job titles frequency by province
  2. Waffle Chart: Job type proportion by region
  3. Various Plots: Relationship between vacancies and company revenue


Insights & Reflection
  1. Which job types appear most frequently across Canada?
  2. Which provinces show the strongest demand for IT and Food-related jobs?
  3. What correlations exist between company revenue and total vacancies?
  4. What could explain any “outliers” in the regression plot?


How to Run
  1. Upload this notebook and dataset to Google Colab
  2. Run the first cell to install libraries:
        !pip install pywaffle wordcloud ipywidgets
  3. Run all cells in order (Runtime → Run all)
  4. Use the dropdown menu to explore provinces interactively



Credits
  Author: Danny Tang
  Course: NPower Canada — Junior Data Analyst Program
  Module: Course 8, Module 3 — Data Visualization with Python
  Date: October 2025

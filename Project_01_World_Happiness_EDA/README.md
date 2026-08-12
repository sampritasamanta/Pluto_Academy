# Project 01 — World Happiness Report EDA

## Overview

This project was completed as part of the Pluto Academy AI & ML Internship Program.

The objective is to perform Exploratory Data Analysis (EDA) on the World Happiness Report dataset and identify important patterns, trends, and relationships affecting happiness scores across countries from 2015 to 2019.

## Dataset

**World Happiness Report Dataset — 2015 to 2019**

Source: Kaggle  
https://www.kaggle.com/datasets/unsdsn/world-happiness

The dataset contains information about countries and several factors related to their happiness scores, including:

- Happiness Score
- Happiness Rank
- GDP per Capita
- Social Support
- Health
- Freedom
- Generosity
- Corruption

## Data Preparation

The original dataset consisted of five yearly CSV files:

- 2015
- 2016
- 2017
- 2018
- 2019

Because the column names differed between years, they were standardized before combining the datasets.

The final cleaned dataset contains:

- **782 rows**
- **10 columns**
- **0 missing values**
- **0 duplicate rows**

## Analysis Performed

The project includes:

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Missing-value analysis
4. Duplicate-value analysis
5. Descriptive statistics
6. Exploratory Data Analysis
7. Year-wise happiness analysis
8. Top-ranked countries analysis
9. Correlation analysis
10. Data visualization

## Visualizations

The notebook contains at least six different visualization types:

- Bar chart
- Line chart
- Histogram
- Scatter plot
- Pie chart
- Correlation heatmap

Each visualization includes appropriate titles and labels.

## Key Findings

The analysis examines the relationship between happiness and factors such as GDP per Capita, Social Support, Health, Freedom, Generosity, and Corruption.

The strongest observed relationship with Happiness Score was GDP per Capita, followed by Health and Social Support.

Detailed findings and conclusions are provided in the notebook.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

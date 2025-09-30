# West Nile Virus Mosquito Analysis - Chicago 2008-2019

## Project Overview

This project analyzes West Nile Virus (WNV) prevalence in Chicago's mosquito population from 2008-2019 using trap monitoring data. The analysis includes data cleaning, exploratory data analysis (EDA), and statistical modeling to understand factors affecting mosquito populations and WNV occurrence.

## Dataset Description

The dataset contains mosquito trap monitoring records from Chicago with the following key features:
- **Temporal**: Year, Week, Date
- **Spatial**: Address Block, Latitude, Longitude
- **Trap Information**: Trap ID, Trap Type
- **Biological**: Mosquito Species, Mosquito Number, WNV Present

## Project Structure

- `notebooks/`: Jupyter notebooks containing analysis
  - `01_data_cleaning_and_eda.ipynb`: Data wrangling and exploratory analysis
  - `02_statistical_analysis.ipynb`: Statistical modeling and hypothesis testing
- `data/`: Raw and processed datasets
- `src/`: Python utility functions
- `reports/`: Generated figures and summary reports

## Key Findings

### Part 1: Data Cleaning & EDA
- Dataset contains [X] records across [Y] years
- Identified seasonal patterns in mosquito populations
- Found species-specific WNV prevalence rates

### Part 2: Statistical Analysis
- Average monthly mosquito counts show peak activity in [summer months]
- Significant correlation between [variables] and mosquito numbers
- Logistic regression model achieved [X]% accuracy in WNV prediction

## Requirements
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scipy>=1.7.0
scikit-learn>=1.0.0
jupyter>=1.0.0
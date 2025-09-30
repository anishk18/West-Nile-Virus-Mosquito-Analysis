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

- [notebooks/](notebooks): Jupyter notebooks containing analysis
  - [`01_data_cleaning_and_eda.ipynb`](notebooks/01_data_cleaning_and_eda.ipynb): Data wrangling and exploratory analysis
  - [`02_statistical_analysis.ipynb`](notebooks/02_statistical_analysis.ipynb): Statistical modeling and hypothesis testing
- [data/](data): Raw and processed datasets


## Key Findings

### Part 1: Data Cleaning & EDA
- Dataset contains [18495] records across [11] years
- CULEX RESTUANS species-had highest specific WNV prevalence rates
 
### Part 2: Statistical Analysis
- Average monthly mosquito counts show peak activity in May-August
- Significant correlation between all features except trap type and mosquito numbers
- Logistic regression model achieved [81]% accuracy in WNV prediction


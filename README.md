# Evan_Li_IDS706_Hwk3
[![Data Analysis](https://img.shields.io/badge/data%20analysis-complete-brightgreen)](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/blob/main/analysis_results.md)

[![Install](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/actions/workflows//install.yml/badge.svg)](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/actions/workflows/install.yml)
[![Format](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/actions/workflows/format.yml/badge.svg)](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/actions/workflows/format.yml)
[![Lint](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/actions/workflows/lint.yml/badge.svg)](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/actions/workflows/lint.yml)
[![Test](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/actions/workflows/test.yml/badge.svg)](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/actions/workflows/test.yml)


You can find the cloud-hosted notebook here: [Evan Li IDS706 Googl Colab Link](https://colab.research.google.com/drive/1e1IQG0HHfwCZVFfwzpD5rgABEsUzYTtN?usp=sharing)

All code has been executed and markdown text has been added, allowing you to clearly see the documented execution results.

## Dataset Overview

The data is sourced from [Kaggle's Data Engineer Salary in 2024 dataset](https://www.kaggle.com/datasets/chopper53/data-engineer-salary-in-2024). This dataset provides insights into data engineer salaries and employment attributes for the year 2024. It includes information such as:
   - Salary
   - Job title
   - Experience level
   - Employment type
   - Employee residence
   - Remote work ratio
   - Company location
   - Company size

## Actions
1. `make install` to install all the required packages.

## Data Analysis
Analyzed and plotted the following items:
- Statistical data and distribution of all salaries
- Job Title Distribution
- Experience Level Distribution
- Average Salary By Job
- Salary Statistics by Experience Level

In addition to the Jupyter notebook execution results, you can find the markdown documentation generated from the code execution here: [Analysis file](https://github.com/bionicotaku/Evan_Li_IDS706_Hwk11/blob/main/analysis_results.md).

## Project Features
1. Python script reading the dataset and generating descriptive statistics with data visualization, finally summarizing and creating an analysis_results.md file. (All Pandas library calls, analysis, and plotting functions are in the mylib/calculate_stat.py file)
2. Using Jupyter Notebook to perform descriptive statistics using Pandas, generating visual files.
3. Creating test_script.py to test the script, test_lib.py to test the library, and finally using the nbval plugin for pytest to test all files including ipynb.
4. Generated 4 badges, each linked to four GitHub actions.

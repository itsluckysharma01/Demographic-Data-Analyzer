# Demographic Data Analyzer

This project analyzes demographic data from the 1994 Census database to answer various questions about the population.

## Dataset

The analysis uses the `adult.data` file containing demographic information with the following columns:

- age
- workclass
- fnlwgt
- education
- education-num
- marital-status
- occupation
- relationship
- race
- sex
- capital-gain
- capital-loss
- hours-per-week
- native-country
- salary

## Analysis Questions

This project answers the following questions:

1. How many people of each race are represented in this dataset?
2. What is the average age of men?
3. What is the percentage of people who have a Bachelor's degree?
4. What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?
5. What percentage of people without advanced education make more than 50K?
6. What is the minimum number of hours a person works per week?
7. What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?
8. What country has the highest percentage of people that earn >50K and what is that percentage?
9. What is the most popular occupation for those who earn >50K in India?

## Files

- `demographic_data_analyzer.ipynb` - Jupyter notebook with the analysis
- `demographic_data_analyzer.py` - Python script version
- `main.py` - Main execution file
- `test_module.py` - Test module
- `adult.data` - Dataset file

## Requirements

- Python 3.x
- pandas
- numpy

## Usage

Run the Jupyter notebook or execute the Python scripts to see the analysis results.

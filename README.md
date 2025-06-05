# DATA ANALYSIS PROGRAMMING

## Project Objectives

In this project, I will analyze data related to premature mortality rates in counties in the United States. Specifically, the project includes:

1. **Data Analysis and Visualization**: Presenting data tables and creating visual charts of the YPLL Rate by county using the pandas and matplotlib libraries.

2. **Building a regression model**: From the `additional-measures.csv` dataset, I will use other indicators to predict the premature mortality rate (YPLL Rate). This is an important step in understanding the relationship between health indicators and mortality rates.

## Part 1:

Using the `ypll.csv` dataset containing the rate of premature death per 100,000 people in each county in the United States with the following attributes:

- FIPS: county code
- State: state
- County: county
- Unreliable: flags a row of data that may be incorrectly captured
- YPLL Rate: premature death rate per 100,000

The YPLL dataset is used to measure premature death (before age 75). Each row of data is measured in 100,000 people (one hundred thousand people) and the total number of years they died before age 75. For example, a person who died at age 73 is considered to have died 2 years prematurely. If they died at age 77, the number of years they died prematurely is 0 years.

## Part 2:

Using the `additional-measures.csv` dataset

This dataset contains all the other metrics in each County. Your task is to build a model to predict the YPLL Rate premature mortality based on the other metrics.

## Highlights

- **Use pandas** to process and analyze data quickly and easily.

- **Data visualization with matplotlib**: Create vivid and intuitive charts, making it easy to analyze and draw conclusions.

- **Prediction using machine learning models**: Build a model to predict mortality based on independent variables from other datasets.

## Value brought

The project is not just a regular data analysis exercise, but it also opens up a deep perspective on public health, helping to better understand the disparities in premature mortality between counties in the United States. With the predictive model, I hope to create a useful tool to predict mortality based on important health factors.

Please see and refer to my source code. Hopefully what you learn from this project will help you in other data analysis projects, it will give you useful ideas, as well as in your career development of programming skills.

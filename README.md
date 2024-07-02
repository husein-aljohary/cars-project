
# Cars Data Cleaning and Analysis

## Overview

This project focuses on cleaning and analyzing a dataset of cars. The primary goal is to handle missing values and perform exploratory data analysis (EDA) to gain insights into the dataset.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data Cleaning Steps](#data-cleaning-steps)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project, you will need the following libraries:
- pandas
- numpy
- matplotlib
- seaborn

## Usage
- Clone this repository.
- Open the Jupyter notebook cars.ipynb.
- Run the cells sequentially to perform data cleaning and analysis.

## Data Cleaning Steps
1. Handling Missing Values
- Model Year: Filled missing values using the median and verified that the distribution remained unchanged.
- Cylinders: Used groupby with mode to fill missing values with the most frequent value.
- Odometer: Replaced missing values with the median to maintain data integrity.
- Paint Color: Assigned 'NA' to missing values due to the lack of a predictive relationship.
- Is 4WD: Since only one value was missing, filled it appropriately.

2. Other Cleaning Steps
- Addressed outliers and ensured the data distribution was consistent post-cleaning.

## Exploratory Data Analysis
- Price Analysis: Investigated the price distribution and identified potential anomalies.
- Car Models: Analyzed the distribution of various car models.
- Cylinders: Examined the distribution of the number of cylinders.
- Drive Type: Compared the prevalence of two-wheel drive versus four-wheel drive vehicles.
- Fuel Type: Analyzed the types of fuel used.
- Transmission: Investigated the distribution of transmission types.
- Car Type: Linked car types with their prices to understand their relationship.

## Conclusion
The project involved extensive data cleaning and analysis, resulting in cleaned data and several insights about the cars dataset.

## Recommendations
- Prioritize models like Ford F150, Chevrolet Silverado 1500, and Ram 1500 based on their prevalence.
- Focus on improving the data collection process to reduce the occurrence of missing values.

## [Tableau](https://public.tableau.com/app/profile/husein.aljohary8537/viz/carsproject_17166522993620/Dashboard1)

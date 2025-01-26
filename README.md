# Palmer-Penguins-Dataset-Analysis-in-R
My first R Notebook experience: Using Professor Martin Van Waerebeke's tutorial on EDA with R.

## Overview
This project analyzes the `palmerpenguins` dataset using R, performing exploratory data analysis (EDA), handling missing values, computing basic statistics, and visualizing relationships between features.

## Requirements
- R (version 4.0 or higher)
- Required Packages:
  ```r
  install.packages("palmerpenguins")
  ```
- Dataset: Provided in the `palmerpenguins` package.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Sourena-Mohit/Palmer-Penguins-Dataset-Analysis-in-R.git
   cd Palmer-Penguins-Dataset-Analysis-in-R
   ```
2. Open R and run:
   ```r
   rmarkdown::render("Penguin_Analysis.Rmd")
   ```

## Features
- Loads the `palmerpenguins` dataset
- Inspects data structure and handles missing values
- Computes summary statistics (mean, median, variance, correlation)
- Performs data filtering and feature engineering (e.g., BMI calculation)
- Visualizes data using histograms, scatter plots, and bar plots

## License
This project is licensed under the MIT License.

# ANA_515P_Data_Cleaning: NFL Elo Data 
This repository contains the R code and datasets used for analyzing and cleaning NFL Elo data. The project focuses on cleaning the data, handling missing values, and visualizing key variables such as Elo ratings and team scores for various NFL games.

# Project Overview
The key objectives of this project are:

## Data Cleaning:
Handle missing values, fix data types, and remove invalid records from the NFL Elo dataset.
## Data Visualization:
Use histograms, box plots, and scatter plots to explore and visualize important variables.

## Data Cleaning steps used:
- Conversion of the date column to the correct date format.
- Correction of data types for numeric columns (e.g., Elo ratings, QB Elo ratings).
- Removal of rows with missing values (NA), zeros, or empty strings in relevant columns.
- Imputation of inconsistent values in the season and elo1_pre columns.
- Saving the cleaned dataset for further use.

# Files in This Repository
- data_cleaning.Rmd: R Markdown file containing the R code for cleaning the dataset, performing data analysis, and visualizing key metrics.
- cleaned_data.xlsx: The cleaned version of the NFL Elo dataset, generated after the cleaning process.
- nfl_elo_latest.xlsx: The original dataset used for this analysis before any cleaning.
- nfl_elo_original.xlsx: Another original dataset used in this analysis before cleaning.
- README.md: This file, explaining the project details, usage instructions, and dataset information.
# How to Use This Repository
## Prerequisites
Make sure you have the following packages installed in R:

- tidyverse
- lubridate
- ggplot2
- writexl
- readxl
## Instructions
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/<your-username>/nfl-elo-analysis.git
Open the data_cleaning.Rmd file in RStudio or any R environment.
Run the R code to clean the data, generate visualizations, and save the cleaned dataset as cleaned_data.xlsx.

Note: You can also edit the file to apply additional transformations or visualizations as needed.


"Uploaded original datasets for NFL Elo data analysis project."

Contact Information
For any questions or issues regarding this repository, please contact:

Alissitz: alissitz@mcdaniel.edu

# NFL Team Performance Data Wrangling Project

## Table of Contents
- [Project Overview](#project-overview)
- [Folder Structure](#folder-structure)
- [Data Sources](#data-sources)
- [Data Dictionary](#data-dictionary)
- [Project Workflow](#project-workflow)
- [Jupyter Notebooks](#jupyter-notebooks)

## Project Overview
This project aims to analyze NFL team statistics from 2010 to 2023 to determine key factors contributing to team success. We explore various performance metrics like turnovers, big plays, and yards per play and how they relate to a team’s win percentage.

## Folder Structure
- `Data/`
  - `Raw/`: Contains the raw data files from external sources (e.g., Kaggle and NFL.com).
    - `team_stats_2010_2023.csv` (NFL team stats from 2010 to 2023)
    - `nfl_passing_stats.csv` (NFL passing stats)
  - `Cleaned/`: Contains the cleaned and processed data that is ready for analysis.
    - `nfl_team_stats_df.csv`

- `Code/`: Contains Jupyter Notebooks for data wrangling and analysis.
  - `NFL Analysis.ipynb` — the main notebook where data wrangling and analysis are performed.
    
-  `Report/`: Final write-up discussing data analysis, methodology, model results, and conclusions.
  - `NFL Report - BAIS Project.pdf`
       
- `Notebooks/`: Contains documentation files.
  - `data_dictionary.md`: Describes the data dictionary, explaining the columns in the dataset.

## Data Sources
The raw data used in this project is sourced from:
- [Kaggle NFL Team Data (2003-2023)](https://www.kaggle.com/datasets/nickcantalupa/nfl-team-data-2003-2023)
- [NFL.com Team Stats (2010-2023)](https://www.nfl.com/stats/team-stats/offense/passing/2010/reg/all)

## Data Dictionary

This dictionary explains the columns and their meanings in the dataset.

| Column Name        | Description                                               |
|--------------------|-----------------------------------------------------------|
| `Year`             | The year of the team’s stats                              |
| `Team`             | Name of the team                                          |
| `Cmp %`            | Percentage of passes completed                            |
| `Yds/Att`          | Yards gained per pass attempt                             |
| `Rate`             | Combined passing rating for QBs                           |

## Project Workflow
1. **Data Acquisition**: The data is sourced from Kaggle and NFL.com.
2. **Data Wrangling**: The data is cleaned and merged to remove inconsistencies and ensure consistency across the dataset.
3. **Analysis**: Various statistical analyses, including correlation and regression, are performed on the cleaned data.
4. **Final Output**: The cleaned data and analysis results are stored in the `cleaned/` folder.

## Jupyter Notebooks
- `Code/NFL Analysis.ipynb`: This notebook contains the data wrangling process, from loading the raw data to cleaning and preparing the data for analysis.

# Task1-Data-Cleaning-and-Preprocessing

## Objective: 
Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).

## Dataset
- *Source*: Netflix Movies and TV Shows on Kaggle
- *Columns*: show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description
  
## Tools Used
- Python
- Pandas
- Jupyter Notebook
  
##  Cleaning Steps Performed
- Handled missing values:
  - Filled director, cast, country with default placeholders
  - Converted date_added to datetime
- Extracted:
  - added_year and added_month from date_added
  - duration_value and duration_unit from duration
- Renamed columns to lowercase with underscores
- Removed any duplicates

## Files Included
- `Data Cleaning and Preprocessing.ipynb` — Jupyter notebook with full cleaning code
- `netflix_titles Dataset.csv` — Dataset

##  Outcome
A cleaned dataset ready for visualization, storytelling, or predictive modeling.

 

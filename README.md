# ELEVATE_LABS_DA_INTERNSHIP_DAY1_TASK1
Task 1: Data Cleaning and Preprocessing Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).

Netflix Dataset Analysis - Project Steps:-
1. Dataset Loading(In Google Collab)
Loaded Netflix movie dataset CSV into a pandas DataFrame
Loaded Netflix TV dataset CSV into another pandas DataFrame

2. Data Profiling(In Google Collab)
Displayed initial rows of both datasets
Explored dataset structure and column information
Identified key columns such as title, director, cast, country, releaseyear, rating, genres, popularity, budget, and revenue

3. Data Cleaning(In Google Collab)
Checked for duplicate rows and confirmed none present
Investigated missing values column-wise and calculated missing percentages
Used heatmap visualization to understand null value distribution for both datasets
Filled or handled missing values appropriately where needed

4. Data Preprocessing(In excel Power Query)
Split columns containing multiple values (e.g., country, genres) by commas into multiple rows for easier readability
Adjusted data types as needed, e.g., changed budget and revenue from float/int to currency
Rounded rating columns to 1 decimal place for uniformity
Renamed dateadded column to releasedate in both datasets for consistency
Dropped irrelevant columns such as voteaverage which added no value

5. Data Standardization (In Excel Power Query)
Imported cleaned datasets into Excel Power Query Editor
Changed data types and applied transformations to standardize format
Ensured column names and data types matched across datasets for merging

6. Dataset Merging(In Excel Power Query)
Verified columns and data types aligned between movie and TV datasets
Appended both datasets to create a single comprehensive Netflix dataset with all rows combined

7. Final Dataset Overview
Combined dataset has a total of approximately 52,750 movie records and 33,432 TV show records

Saved the cleaned and merged dataset for further analysis or visualization

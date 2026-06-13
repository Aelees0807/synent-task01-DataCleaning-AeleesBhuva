# Task 1: Data Cleaning & Preprocessing

## Problem Statement
The objective of this task is to clean and prepare raw data for analysis.This includes addressing missing data, eliminating redundancies, standardizing data formats, and engineering new features to ensure the dataset is clean and ready for analysis. 

## Dataset Details
* **Dataset Name:** Titanic Dataset :  https://www.kaggle.com/datasets/brendan45774/test-file
* **Source:** Kaggle 
* **Original Shape:** 418 rows, 12 columns

## Approach
The development was executed in a Jupyter Notebook using Python (`pandas`, `numpy`, `matplotlib`, `seaborn`), following a standard Data Science workflow for data cleaning. 

The following steps were performed:
* **Handled Missing Values:** 
    * Imputed `Age` with the median value.
    * Imputed `Embarked` with the mode.
    * Dropped the `Cabin` column due to a high volume of missing data.
* **Removed Duplicates:** Executed standard deduplication to ensure data integrity.
* **Converted Data Types:**  
    * Cast `Survived` and `Pclass` to categorical data types for appropriate handling.
* **Renamed Columns:** 
    * Improved clarity by mapping `Pclass` to `Passenger_Class`, `SibSp` to `Siblings_Spouses`, and `Parch` to `Parents_Children`.
* **Feature Engineering:** * Created `Family_Size` by combining siblings/spouses and parents/children.
    * Created an `Is_Alone` binary indicator based on family size.

## Results
The result is a clean dataset ready for analysis. The final dataset structure contains 418 rows and 13 columns. The cleaned data was successfully exported as `titanic_cleaned.csv` for future exploratory data analysis (EDA).

## Deliverables Included
* Jupyter Notebook containing the full code.
* Original Titanic Dataset.
* Demonstration Video Link: `https://drive.google.com/file/d/1KfX0aDC3mhh3_u9UqvDQNNCmeMvjgcK2/view?usp=sharing`

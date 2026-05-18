# Synent Task 1 - Titanic Data Cleaning

## Problem Statement
Clean and preprocess the Titanic dataset for analysis

## Dataset
- Source: Kaggle Titanic Dataset
- Source link: https://www.kaggle.com/datasets/brendan45774/test-file
- Records: 891 passengers
- Features: 12 columns

## Approach
1. Handled missing values in Age, Embarked
2. Removed Cabin column (>70% missing)
3. Removed duplicates
4. Converted categorical types
5. Created engineered features

## Results
- Reduced missing values from 866 to 0
- Created 2 new features: Family_Size, Is_Alone
- Clean dataset ready for analysis

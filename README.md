# Hepatitis C Prediction

This code is designed to analyze and predict the presence of Hepatitis C based on a dataset containing various medical and demographic information.
The notebook focuses on the analysis and prediction of Hepatitis C stages using a machine learning approach. The dataset includes medical test results and demographic details.

## Data Preprocessing
- Removal of unnecessary columns, such as the "Unnamed" column.
- Conversion of categorical values to numerical values for convenience:
  - Category column:
    - 0 -> Blood Donor
    - 1 -> Suspect Blood Donor
    - 2 -> Hepatitis
    - 3 -> Fibrosis
    - 4 -> Cirrhosis
  - Sex column:
    - 0 -> Male
    - 1 -> Female

## Exploratory Data Analysis (EDA)
- Initial examination of the dataset to understand its structure, distributions, and patterns.

## Handling Null Values
- Null values in the columns "ALB", "ALP", "ALT", "CHOL", and "PROT" are replaced using the mode method due to the small number of nulls.

## Building Prediction Models
- The notebook includes steps to build and evaluate machine learning models for predicting Hepatitis C stages.

## Conclusion
This notebook provides a comprehensive approach to preprocessing, analyzing, and modeling data for predicting Hepatitis C stages, offering insights and methodologies that can be applied to similar medical datasets.

## Dependencies
- Python libraries required include pandas, numpy, matplotlib, seaborn, scikit-learn, etc.

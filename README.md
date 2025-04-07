# Customer-Personality-Dataset-Cleaning
# Data Cleaning Task

## Objective
The goal of this task was to clean a raw dataset named `marketing_campaign.csv` by handling missing values, removing duplicates, standardizing formats, and fixing data types.

## Tools Used
- Python
- Pandas
- Google Colab Notebook

## Summary of Work
- The original dataset is provided as `marketing_campaign.csv`.
- The cleaned and processed version is saved as `cleaned_dataset.csv`.
- All cleaning steps have been implemented in the attached Jupyter Notebook: `Dataset_Cleaning.ipynb`.

## Cleaning Steps Performed
- Replaced missing values in the `Income` column with the median.
- Removed duplicate rows.
- Standardized text values (e.g., formatting in `Marital_Status`).
- Converted `Dt_Customer` to datetime format.
- Renamed column headers to lowercase and replaced spaces with underscores.
- Ensured proper data types across all columns.

The dataset is now cleaned and ready for further analysis or modeling.

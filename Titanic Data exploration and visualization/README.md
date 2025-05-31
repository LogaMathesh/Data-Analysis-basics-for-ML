# Data Analysis basics for ML

This project is a beginner-friendly walkthrough of data cleaning and analysis using the Titanic dataset.

## What’s Covered
- Handling missing values
- Encoding categorical variables
- Visualizing data (age distribution, survival count by sex)
- Exporting cleaned dataset

## Folder Structure
- `Dataset/raw dataset/`: Original dataset from Kaggle
- `Dataset/ Titanic/`: Cleaned dataset after analysis
- `notebooks/`: ipynb file in VSCode

## Libraries Used:
- seaborn
- pandas
- matplotlib

## 🔄 Update - [2025-05-31]
- Dropped unwanted columns for cleaner analysis
- Added feature engineering: family size, age bin, fare bin
- Improved plots: scatter plot and heatmap

# Drop redundant/derivable columns
# ⚠️ Note: These columns may have already been deleted earlier in the workflow.
# If they are missing, this will raise a KeyError. Uncomment the line below only if the columns still exist.
# df.drop(['alive', 'class', 'who', 'adult_male', 'alone'], axis=1, inplace=True)

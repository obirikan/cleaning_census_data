# Census Data Analysis

This project analyzes US Census data to explore demographic trends across different states. The dataset includes information on population, race, income, and gender distribution.

## Project Overview

The analysis focuses on:
- Combining multiple state datasets into a single dataframe
- Cleaning and reshaping the data for analysis
- Handling duplicates and missing values
- Exploring demographic patterns

## Data Cleaning Steps

1. **Combined Data**: Merged multiple state CSV files into a single DataFrame
2. **Reshaped Data**: Used `pd.melt()` to transform race columns into rows
3. **Handled Duplicates**: Removed 54 duplicate rows
4. **Cleaned Features**:
   - Removed '$' and ',' from Income values
   - Split GenderPop into separate male and female population columns
   - Removed '%' from PopPercentage values
5. **Missing Values**: Identified 12 missing female population values and 4 missing percentage values

## Key Files
- `main.ipynb`: Jupyter notebook containing the cleaning process
- `census_analysis.ipynb`: Jupyter notebook containing the full analysis //todo
- `dataset/`: Folder containing the original state CSV files

## Technologies Used

- Python 3
- Pandas
- Jupyter Notebook

## How to Use

1. Clone this repository
2. Ensure all CSV files are in the `dataset/` folder
3. Run the Jupyter notebook 

## Future Work

- Visualize demographic distributions
- Calculate gender ratios by state
- Analyze income disparities across racial groups
- Handle missing values more robustly

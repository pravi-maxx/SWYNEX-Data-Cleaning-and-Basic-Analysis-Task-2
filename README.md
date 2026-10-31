# SWYNEX Data Cleaning and Basic Analysis

Task 2 of the SWYNEX internship. A Python (pandas) notebook that cleans a messy sequence dataset and summarizes it.

## Steps
1. Load and inspect data (shape, missing values, duplicates)
2. Clean: remove duplicates, standardize text, drop invalid sequences, fill missing values, remove outliers (IQR)
3. Sequence summaries: length and GC content
4. Basic statistics and plots

## Run
`pip install pandas numpy matplotlib jupyter` then open `Data_Cleaning_and_Basic_Analysis.ipynb`.

## Files
- `Data_Cleaning_and_Basic_Analysis.ipynb`: main notebook
- `cleaned_dataset.csv`, `summary_statistics.csv`: outputs
- `histograms.png`, `organism_counts.png`: plots

# DataX-Labs-Tasks
Task 1:

Initial Inspection:
Performed an initial overview of the dataset to understand its structure, check data types, identify missing values, and detect duplicate records.

Column Names Check:
Verified that all column headers were properly formatted with no spaces or special characters. No renaming was required.

Handling Missing Values:
Filled categorical columns such as make and model using their most frequent values (mode).

For model, missing entries were imputed using the mode within each make group to maintain consistency.

The transmission column, having around 10% missing values, was also filled with its mode.

Columns with excessive missing values, like trim, were dropped to prevent bias.

Text Standardization:
Converted text-based columns like body to lowercase for uniform formatting and easier grouping during analysis.

Data Type Correction:
Converted the saledate column from object to datetime format with timezone handling.

Ensured the year column was stored as an integer for numerical operations.

Data Consistency Check:
Validated numeric and categorical columns for correct ranges, formats, and logical consistency after cleaning.

Final Output:
The cleaned dataset now contains 548,170 rows and 16 columns, free from major missing values or inconsistencies, and is ready for Exploratory Data Analysis (EDA).

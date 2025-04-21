# task_1
Data Analytics internship day 1 task

1.Column Normalization :
Renamed all column headers to lowercase and replaced spaces with underscores (e.g., Year_Birth → year_birth).

2.Handling Missing Values:
Dropped rows with excessive nulls beyond a threshold.

3.Removing Duplicates:
Removed exact duplicate rows using .drop_duplicates() to avoid redundancy.

4.Text Standardization :
Standardized categorical text fields like education and marital_status (e.g., unified inconsistent capitalization or trailing spaces).

5.Date Formatting :
Converted the dt_customer column to a standard datetime object using pd.to_datetime().

6.Data Type Correction:
Ensured numeric fields such as year_birth, income, and campaign response flags were stored with appropriate data types (e.g., int, float, boolean).

7.Dropping Irrelevant Columns:
Removed constant-value columns like z_costcontact and z_revenue, which do not contribute meaningful information to the analysis.

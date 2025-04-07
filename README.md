# Data_analysis
1. Column Renaming and Standardization
Column names were standardized (e.g., capitalized and formatted):

title → Title

type → Type

release_year → Release Year

date_added → Date Added

listed_in → split into Gnere 1 and Genre 2 (probably a typo in "Gnere")

duration was split into two separate columns:

Duration Value (numeric part)

Duration Type (e.g., "min", "Season")

2. Handling Missing Values
Some missing values were reduced or filled:

director, cast, and country columns have significantly fewer missing values in the cleaned data.

However, some fields like Date Added, Rating, and Description still have a small number of missing values.

3. Data Transformation
duration column was parsed into:

Duration Value: Extracted the numeric part (e.g., 90)

Duration Type: Extracted the unit (e.g., "min" or "Season")

4. Genre Extraction
listed_in appears to have been split into multiple genre columns: Gnere 1 and Genre 2, to better categorize multi-genre entries.

5. Preserved Data
Row count remains the same: 8,807 rows, meaning no rows were dropped during cleaning, just modified.

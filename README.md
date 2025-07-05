1. Import Required Libraries
   import numpy as np
   import pandas as pd
   import matplotlib.pyplot as plt
   import seaborn as sns
   import warnings
   warnings.filterwarnings("ignore")
   Imports libraries for data analysis (pandas, numpy), visualization (matplotlib, seaborn), and suppresses warnings.

2. Load the Dataset
    Loads the dataset from a CSV file and prints all rows to inspect raw data.

3. Initial Data Overview
    info(): Displays column types and non-null values.
    describe(): Gives statistical summary of numeric columns.

4. Check for Duplicates
    Finds the number of duplicate rows.

5. Remove Duplicates
    Removes all duplicate entries from the dataset.

6. Convert Age to Numeric
    Converts the Age column to numeric, replacing invalid values with NaN.

7. Check Unique Age Values
    Lists all unique values in the Age column after conversion.

8. Fill Missing Age Values with Median
    Calculates the median age and fills missing values with it.

9. Standardize Gender Values
    Replaces inconsistent gender entries with standardized values.

10. Fill Missing Email Values
    Replaces missing values in the Email column with "-".

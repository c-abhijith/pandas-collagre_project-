pip --default-timeout=1000 install pandas

1. DataFrame and Series Creation
pd.DataFrame(): Create a DataFrame from a dictionary, list, or other data structures.

pd.Series(): Create a Series (a single column of data).

pd.read_csv(): Read data from a CSV file into a DataFrame.

pd.read_excel(): Read data from an Excel file into a DataFrame.

pd.read_json(): Read data from a JSON file into a DataFrame.

pd.read_sql(): Read data from a SQL database into a DataFrame.

2. Data Inspection
df.head(): Display the first few rows of the DataFrame.

df.tail(): Display the last few rows of the DataFrame.

df.info(): Display summary information about the DataFrame (e.g., column names, data types, non-null counts).

df.describe(): Generate descriptive statistics for numerical columns.

df.shape: Get the dimensions of the DataFrame (rows, columns).

df.columns: Get the column names.

df.index: Get the row indices.

df.dtypes: Get the data types of each column.

3. Data Selection and Indexing
df[column]: Select a single column (returns a Series).

df[[col1, col2]]: Select multiple columns (returns a DataFrame).

df.loc[]: Label-based indexing (rows and columns).

df.iloc[]: Integer-based indexing (rows and columns).

df.at[]: Access a single value by row and column label.

df.iat[]: Access a single value by row and column index.

df.filter(): Filter rows or columns based on labels.

df.query(): Query the DataFrame using a boolean expression.

4. Data Cleaning
df.drop(): Drop rows or columns.

df.dropna(): Drop rows or columns with missing values.

df.fillna(): Fill missing values with a specified value or method.

df.replace(): Replace values in the DataFrame.

df.duplicated(): Check for duplicate rows.

df.drop_duplicates(): Remove duplicate rows.

df.rename(): Rename columns or index labels.

df.set_index(): Set a column as the index.

df.reset_index(): Reset the index to the default integer index.

5. Data Manipulation
df.sort_values(): Sort the DataFrame by one or more columns.

df.sort_index(): Sort the DataFrame by the index.

df.groupby(): Group data by one or more columns for aggregation.

df.pivot_table(): Create a pivot table.

df.melt(): Unpivot a DataFrame from wide to long format.

df.pivot(): Reshape the DataFrame based on column values.

df.merge(): Merge two DataFrames based on a key.

df.join(): Join two DataFrames based on the index.

df.concat(): Concatenate DataFrames along a specified axis.

df.apply(): Apply a function to each row or column.

df.map(): Apply a function to each element of a Series.

df.transform(): Apply a function to each group or element.

6. Data Aggregation
df.sum(): Compute the sum of values.

df.mean(): Compute the mean of values.

df.median(): Compute the median of values.

df.min(): Compute the minimum value.

df.max(): Compute the maximum value.

df.count(): Count non-null values.

df.agg(): Apply multiple aggregation functions at once.

df.cumsum(): Compute the cumulative sum.

df.cumprod(): Compute the cumulative product.

7. Handling Missing Data
df.isna(): Check for missing values.

df.notna(): Check for non-missing values.

df.fillna(): Fill missing values.

df.dropna(): Drop missing values.

df.interpolate(): Interpolate missing values.

8. Time Series Operations
pd.to_datetime(): Convert a column to datetime format.

df.resample(): Resample time series data.

df.shift(): Shift data forward or backward in time.

df.rolling(): Compute rolling window calculations.

df.diff(): Compute the difference between consecutive elements.

9. Input/Output (I/O)
df.to_csv(): Write the DataFrame to a CSV file.

df.to_excel(): Write the DataFrame to an Excel file.

df.to_json(): Write the DataFrame to a JSON file.

df.to_sql(): Write the DataFrame to a SQL database.

df.to_dict(): Convert the DataFrame to a dictionary.

10. Visualization
df.plot(): Create basic plots (line, bar, histogram, etc.).

df.hist(): Create histograms.

df.boxplot(): Create box plots.

11. Advanced Operations
df.corr(): Compute the correlation matrix.

df.cov(): Compute the covariance matrix.

df.eval(): Evaluate a string expression on the DataFrame.

df.explode(): Transform each element of a list-like column to a row.

12. Memory Optimization
df.memory_usage(): Check memory usage of each column.

df.astype(): Change the data type of columns to reduce memory usage.
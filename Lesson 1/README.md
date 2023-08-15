# Data Manipulation with pandas - Lesson 1 Summary

In this first lesson on data manipulation with pandas, I've learned the fundamental concepts and techniques for transforming and summarizing data using pandas. Here's a breakdown of what I've covered:

## Transforming Data

### Introduction to Dataframes
- Pandas is a powerful Python library used for data manipulation and analysis.
- Dataframes are the core data structure in pandas, built upon Numpy and Matplotlib.

### Importing and Inspecting Data
- I've imported a dataset using `pd.read_csv()` and examined its initial rows using `head()`.
- Utilized `info()` to gather information about the dataset's columns, data types, and missing values.
- Explored the dataframe's dimensions with `shape`.
- Calculated basic statistics with `describe()`.

### Parts of a DataFrame
- Explored the components of a dataframe: columns, index, and values.

### Sorting and Subsetting
- Used `sort_values()` to arrange data based on specific columns in ascending or descending order.
- Selected columns and subsets of rows based on conditions.

### Creating New Columns
- Created new columns by performing calculations on existing data.
- Introduced the concept of transforming data to derive insights.

## Aggregating Data

### Summary Statistics
- Calculated summary statistics such as mean, median, and more using built-in functions.
- Explored custom functions and applied them using `.agg()`.

### Counting and Duplicates
- Removed duplicate rows using `drop_duplicates()` and explored unique value counts using `value_counts()`.

### Grouped Summary Statistics
- Used the `groupby()` function to aggregate data by specific columns.
- Calculated mean values for state population in different regions.

### Pivot Tables
- Introduced pivot tables as an alternate method for summarizing data.
- Demonstrated how to create pivot tables using the `pivot_table()` function.
- Explored options like specifying aggregation functions, handling NaN values, and calculating margins.

These concepts provide a solid foundation for data manipulation and analysis using pandas. I'm excited to continue building on these skills and exploring more advanced techniques in subsequent lessons.

# Week 07

## [**`Introduction to Pandas`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/01%20Introduction%20to%20Pandas.ipynb)

- Key Features and Benefits
  - Data Structures for Efficient Data Manipulation
  - Handling Missing Data
  - Merging, Joining Datasets and Concatenation
  - String, Datetime, and Categorical Data Functionality
  - Integration with Other Libraries and Tools
- Pandas Data Structures
  - Overview of Series and DataFrame
  - Series
  - DataFrame
- Getting Started with Pandas
- Installation
- Importing Pandas
- Basic Usage Examples
  - Creating a Series
  - Creating a DataFrame
  - Accessing Data
- Pandas Datatypes

## [**`Pandas Series`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/02%20Pandas%20Series.ipynb)

- Creating a Series
  - Creating a Series from a List, NumPy Array, or Dictionary
  - Specifying an Index when Creating a Series
  - Using the ‍`pd.Series()` Constructor
- Series Attributes
  - `dtype`: Data Type of the Series Elements
  - `shape`: Tuple of Series Dimensions
  - `size`: Number of Elements in the Series
  - `index`: Index Object of the Series
  - `values`: NumPy Array of Series Values
- Vectorized Operations and Label Alignment
  - Vectorized Operations
  - Label Alignment
- Common Series Methods
  - `head()` and `tail()`: Viewing the First or Last n Elements
  - `unique()`: Returning Unique Values in a Series
  - `value_counts()`: Counting Occurrences of Unique Values
  - `sort_values()`: Sorting a Series by Values
  - `sort_index()`: Sorting a Series by Index
- Converting Series Data Types
  - Using `astype()` for Explicit Conversion
  - Handling Numeric Conversions
  - Converting to Datetime
  - Converting to Categorical Data
  - Best Practices and Considerations
- Conclusion

## [**`Pandas DataFrame`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/03%20Pandas%20Dataframes.ipynb)

- Creating DataFrames
  - From dict of Series or dicts
  - From dict of ndarrays / lists
  - From structured or record array
  - From a list of dicts
  - From a dict of tuples
  - From a Series
  - From a list of namedtuples
  - From a list of dataclasses
  - Alternate constructors
- DataFrame Attributes and Methods
  - Attributes
  - Methods
- [Data Alignment and Arithmetic
  - Arithmetic Operations between DataFrames
  - Arithmetic Operations between DataFrames and Series
  - Flexible Arithmetic Methods
- Console Display
  - Displaying the DataFrame in the Console
  - Customizing the Display Settings
  - Hiding or Showing Index and Column Labels
- Conclusion

## [**`Basic Indexing and Selecting Data`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/04%20Basic%20Indexing%20and%20Selecting%20Data.ipynb)

- Different Choices for Indexing
- Basics of Indexing and Selection
  - Accessing Elements in a Series
  - Selecting Columns in a DataFrame
  - Selecting Rows in a DataFrame
  - Slicing Rows and Columns
- Selecting Random Samples
- Fast Scalar Value Getting and Setting
  - Using `at` for Fast Scalar Value Getting and Setting
  - Using `iat` for Fast Scalar Value Getting and Setting
- Performance Considerations

## [**`More on Indexing`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/05%20More%20on%20Indexing.ipynb)

- Boolean Indexing
  - Creating Boolean Masks
  - Selecting Rows and Columns Based on Boolean Conditions
  - Combining Boolean Conditions Using Logical Operators
  - Practical Examples and Use Cases
- Indexing with `isin`
  - Selecting Rows Based on a List of Values
  - Filtering Data Using `isin()`
  - Combining `isin()` with Boolean Indexing
  - Practical Examples and Use Cases
- Indexing with query
  - Selecting Data Using String Expressions
  - Filtering Data Based on Complex Conditions
  - When to Use `.query()` vs `.loc`
  - Practical Examples and Use Cases
- Indexing with where
  - Selecting Values Based on a Boolean Mask
  - Replacing Values Based on Conditions
  - Combining where() with Other Indexing Methods
  - Practical Examples and Use Cases
- Hands-on Examples and Exercises
  - Example 1: Boolean Indexing
  - Example 2: Indexing with `isin()`
  - Example 3: Indexing with `query()`
  - Example 4: Indexing with `where()`
- Conclusion

## [**`Multi-Indexing`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/06%20Multi-indexing.ipynb)

- Creating Multi-Index DataFrames
  - From Scratch
  - From Existing DataFrames
  - Using pd.MultiIndex.from_tuples and pd.MultiIndex.from_product
  - Additional Methods
- Accessing and Manipulating Multi-Index Data
  - Basic Indexing and Slicing
  - Using .loc and .iloc
  - [Cross-section Selection with .xs
  - Advanced Selection Techniques
  - Modifying Data
  - Reindexing
- Conclusion and Further Resources

## [**`DataBase Fundamentals`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/07%20Database%20Fundamentals.ipynb)

- Relational Database Concepts
  - Tables, Rows, and Columns
  - Primary Keys and Foreign Keys
  - Relationships Between Tables
- Basic SQL Operations
  - SELECT Statements
  - Filtering with WHERE
  - Sorting with ORDER BY
  - Limiting Results with LIMIT
  - Combining Operations
  - Aggregate Functions
  - GROUP BY
  - HAVING
- Joining Tables
  - Types of Joins
  - INNER JOIN
  - LEFT JOIN
  - RIGHT JOIN
  - FULL OUTER JOIN
- Aggregation and Grouping
  - Aggregate Functions
  - GROUP BY Clause
  - Multiple Aggregations
  - Grouping by Multiple Columns
  - HAVING Clause (Filtering Groups)
- Conclusion

## [**`Applying Functions to Series and DataFrames`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/08%20Applying%20Functions%20to%20Series%20and%20DataFrames.ipynb)

- Applying Functions to Series
  - Using Built-in Functions
  - Applying Custom Functions with .apply()
  - Using .map() for Series Transformation
- Applying Functions to DataFrames
  - Using DataFrame-wide Functions
  - Applying Functions to Columns with .apply()
  - Applying Functions to Rows with .apply(axis=1)
  - Using `.map()` for Element-wise Operations
- Advanced Function Application
  - Vectorized Operations for Performance
  - Using lambda Functions
  - Applying Function to Multiple Columns
  - Applying Multiple Functions with .agg()
- Practical Examples and Use Cases
  - Example 1: Data Cleaning and Transformation
  - Example 2: Text Data Processing

## [**`String Manipulation`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/09%20String%20Manipulation.ipynb)

- Accessing String Methods in Pandas
  - Vectorized Operations
  - Handling Missing Values
  - Method Chaining
  - Accessing Individual Characters
  - Boolean Indexing
  - Applying to DataFrame Columns
  - Regular Expressions
- Basic String Operations
  - Changing Case (lower, upper, title, swapcase)
  - Trimming Whitespace (strip, lstrip, rstrip)
  - Padding Strings (pad, center, ljust, rjust)
- String Information and Checks
  - Length of Strings
  - Checking String Contents (startswith, endswith, contains)
- Extracting and Replacing Substrings
  - Substring Extraction (slice, get)
  - Finding and Replacing (find, replace)
- Regular Expressions in Pandas
  - Introduction to Regular Expressions
  - Using `re.match`, `re.search`, and `re.findall`
  - Extracting Information with Regex
- Splitting and Joining Strings
  - Splitting Strings (split, rsplit)
  - Joining Strings (cat)
- Practical Examples and Use Cases
  - Cleaning and Standardizing Customer Data
  - Parsing and Analyzing Log Data
  - Extracting Information from Product Descriptions
  - Normalizing and Categorizing Text Data

## [**`Date and Time in Pandas`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/10%20Date%20and%20Time%20in%20Pandas.ipynb)

- [Datetime Data Types
  - Timestamp
  - DatetimeIndex
  - Timedelta and TimedeltaIndex
- Creating Datetime Objects
  - Using `to_datetime()`
  - Using `date_range()`
  - Specifying frequency
- Date and Time Components
  - Accessing Components (year, month, day, etc.)
  - Extracting Components to New Columns
- Datetime Indexing and Slicing
  - Partial string indexing
  - Date and time components access
- Parsing and Formatting Dates
  - Parsing Strings to Dates
  - Formatting Dates as Strings
- Conclusion

## [**`Categorical Data`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/11%20Categorical%20Data.ipynb)

- Creating and Converting Categorical Data
  - Creating Categorical Data from Scratch
  - Converting Existing Columns to Categorical
  - Specifying Category Order
- Working with Categorical Data
  - Accessing Categories
  - Adding and Removing Categories
  - Renaming Categories
- Sorting and Ordering Categorical Data
  - Sorting with Ordered Categories
  - Sorting with Unordered Categories
  - Customizing the Sort Order
  - Sorting with Multiple Columns
  - Sorting Index
  - NaN Handling
- Memory Efficiency of Categorical Data
  - Understanding Memory Usage
  - Factors Affecting Memory Efficiency
  - When to Use Categorical Data
  - Impact on Performance
- Encoding Categorical Data
  - One-Hot Encoding
  - Ordinal Encoding
  - Choosing Between One-Hot and Ordinal Encoding
- Practical Examples and Use Cases
  - Example 1: Customer Segmentation
  - Example 2: Product Review Analysis
  - Example 3: Sales Analysis with Seasonal Categories
  - Example 4: Survey Response Analysis

## [**`Handling Duplicate Data`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/12%20Handling%20Duplicate%20Data.ipynb)

- Detecting Duplicate Data
  - Using `.duplicated()` method
  - Identifying duplicate rows
  - Identifying duplicate values in specific columns
- Removing Duplicate Data
  - Using .drop_duplicates() method
  - Removing duplicates based on specific columns
  - Keeping first vs. last occurrence
- Advanced Duplicate Handling
  - Partial duplicates
  - Fuzzy matching for near-duplicates
  - Handling duplicates in time series data

## [**`Handling Missing Values`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/13%20Handling%20Missing%20Values.ipynb)

- Understanding Missing Data
  - Types of Missing Data
  - Impact of Missing Data
  - Assessing Missing Data
  - General Approaches to Handling Missing Data
  - Considerations in Choosing a Method
  - Best Practices
- Values Considered "Missing"
  - NaN (Not a Number)
  - None
  - Custom Missing Value Indicators
- Detecting Missing Values
  - Using `.isnull()` and `.notnull()`
  - Counting Missing Values
- NA Semantics and Behavior
  - Propagation in Arithmetic and Comparison Operations
  - Logical Operations with Missing Values
  - NA in a Boolean Context
- Inserting Missing Data
  - Explicitly Inserting NaN or None
  - Consequences of Inserting Missing Data
- Handling Missing Values
  - Dropping Missing Values
  - Filling Missing Values
  - Interpolation Methods
- Advanced Techniques for Handling Missing Values
  - Using `replace()` for Custom Missing Value Handling
  - Imputation Strategies

## [**`Merging, Joining, and Concatenating DataFrames`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/14%20Merging%2C%20Joining%2C%20and%20Concatenating%20DataFrames.ipynb)

- Concatenating DataFrames
  - Vertical Concatenation (along rows)
  - Horizontal Concatenation (along columns)
  - Handling Index and Axis
- Merging DataFrames
  - Inner Merge
  - Outer Merge
  - Cross Merge
  - Left and Right Merge
  - Merging on Index
  - Merging on Multiple Keys
- Joining DataFrames
  - Understanding the Difference between Merge and Join
  - Different Types of Joins
- Best Practices and Common Pitfalls
  - Best Practices
  - Common Pitfalls

## [**`Grouping and Aggregating Data`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/15%20Grouping%20and%20Aggregating%20Data.ipynb)

- Basic Grouping with `groupby()`
  - Grouping by a Single Column
  - Grouping by Multiple Columns
  - Grouping with a Custom Function
- Aggregation Methods
  - Built-in Aggregation Functions
  - Custom Aggregation Functions
  - Multiple Aggregations
- Advanced Grouping Techniques
  - Using get_group()
  - Filtering Groups
- Transformation and Applying Functions to Groups
  - Using `transform()`
  - Using `apply()`
- Practical Examples and Use Cases
  - Sales Performance Analysis
  - Customer Segmentation
  - Product Affinity Analysis
  - Seasonal Trends Analysis
  - Sales Team Performance Analysis
  - Cohort Analysis

## [**`Reshaping Data ^% Pivoting, Melting, Stacking and Unstacking`**](https://github.com/Yousefess/TA24PYGIS/blob/main/Content/week_07/Notebooks/16%20Reshaping%20Data%5E%25%20Pivoting%2C%20Melting%2C%20Stacking%2C%20and%20Unstacking.ipynb)

- Pivoting Data
  - Using `pivot()`
  - Using `pivot_table()`
- Stacking and Unstacking
  - `stack()` Method
  - `unstack()` Method
- Melting DataFrames
  - `melt()` Function
  - `wide_to_long()` Function
- Exploding List-like Columns
- Cross-tabulation
- Discretization and Categorization
  - `cut()` Function
  - `qcut()` Function (for quantile-based discretization)
- Working with Dummy Variables
  - `get_dummies()`
  - `from_dummies()`

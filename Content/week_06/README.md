# Week 06

## [**`Introduction to NumPy`**]()

- Advantages of using NumPy for Numerical Computing
  - Efficiency and Performance
  - Ease of Use and Readability
  - Integration with Other Libraries
- Key Features and Capabilities of NumPy
  - Multi-dimensional Arrays
  - Mathematical Functions
  - Broadcasting
  - Indexing and Slicing
  - Random Number Generation
  - Saving and Loading Data
- Getting Started with NumPy
  - Installation
  - Importing NumPy
  - Basic Usage Examples
- Summary and Conclusion

## [**`Creating Numpy Arrays`**]()

- Creating 1-Dimensional Arrays
  - Using `np.array()` Function
  - Using `np.arange()` Function
  - Using `np.linspace()` Function
- Creating 2-Dimensional Arrays
  - Using `np.array()` Function with Nested Lists
  - Using `np.zeros()` Function
  - Using `np.ones()` Function
  - Using `np.eye()` Function
  - Using `np.diag()` Function
- Creating Higher-Dimensional Arrays
  - Creating 3-Dimensional Arrays
  - Creating Arrays with More Than 3 Dimensions
- Creating Arrays with Specific Data Types
  - Specifying Data Types Using `dtype` Parameter
  - Common NumPy Data Types
- Random Number Generation
  - Using `np.random.rand()` Function
  - Using `np.random.randn()` Function
  - Using `np.random.randint()` Function
- Conclusion
  - Recap of Key Points
  - Importance of Array Creation in NumPy
  - Further Resources

## [**`Indexing and Slicing Arrays`**]()

- Indexing NumPy Arrays
  - Accessing Elements using Square Bracket Notation
  - Accessing Elements in Multi-dimensional Arrays
  - Using Negative Indices
- Slicing NumPy Arrays
  - Basic Slicing Syntax
  - Slicing Single-dimensional Arrays
  - Slicing Multi-dimensional Arrays
  - Slicing with Step Size
- Advanced Indexing Techniques
  - Boolean Indexing
  - Fancy Indexing
  - Combining Indexing and Slicing
- Modifying Arrays using Indexing and Slicing
  - Assigning Values to Array Elements
  - Modifying Slices of an Array
  - Views vs. Copies in Slicing
    - Views
    - Copies
  - Memory Sharing Check
    - When to Use Views vs. Copies
- Best Practices and Common Pitfalls
  - Avoiding Out-of-Bounds Errors
  - Understanding View vs. Copy Behavior
  - Performance Considerations

## [**`NumPy Data Types`**]()

- Numeric Data Types
  - Integer Types
  - Floating-Point Types
  - Complex Types
- Boolean Data Type
  - Boolean Arrays
  - Boolean Indexing and Masking
- String Data Type
  - Creating String Arrays
  - String Operations
- Object Data Type
- Structured Data Types
  - Creating Structured Arrays
  - Accessing Fields in Structured Arrays
- Casting Data Types
  - Implicit Type Casting
  - Explicit Type Casting
- Memory Considerations
  - Memory Usage of Different Data Types
  - Choosing the Right Data Type
- Best Practices and Tips
  - Specifying Data Types Explicitly
  - Avoiding Unnecessary Type Casting

## [**`Broadcasting`**]()

- Rules of Broadcasting
  - Rule 1: Matching Dimensions
  - Rule 2: Stretching Scalar Values
  - Rule 3: Stretching Arrays with Size 1
- Examples of Broadcasting
  - Scalar and Array Broadcasting
  - One-Dimensional Array Broadcasting
  - Multi-Dimensional Array Broadcasting
  - Broadcasting with Multiple Arrays
- Advantages of Broadcasting
  - Memory Efficiency
  - Concise and Readable Code
- Limitations and Pitfalls of Broadcasting
  - Incompatible Array Shapes
  - Unintended Consequences
- Conclusion

## [**`Vectorization`**]()

- How Vectorization Works
  - Operating on Arrays vs. Individual Elements
  - Under the Hood: NumPy's Optimized C Implementation
- Vectorization vs. Python Loops
  - Performance Comparison
  - Readability and Conciseness
- Writing Vectorized Code
  - Tips and Best Practices
  - Example: Vectorizing a Function
  - Example: Vectorize Computations with `np.vectorize()`
- Pitfalls and Limitations of Vectorization
  - When Vectorization May Not Be Appropriate
  - Memory Considerations
- Summary and Conclusion

## [**`Mathematical Operations with NumPy`**]()

- Element-wise Arithmetic Operations
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Basic Mathematical Functions
  - Trigonometric Functions
  - Exponential and Logarithmic Functions
  - Rounding Functions
- Aggregation Functions
  - Sum
  - Mean
  - Minimum and Maximum
  - Standard Deviation and Variance
- Broadcasting in Mathematical Operations
- Matrix Operations
  - Matrix Multiplication
  - Matrix Transposition
  - Matrix Inversion
- NumPy's Random Number Generation
  - Generating Random Numbers
  - Seeding the Random Number Generator
  - Generating Random Arrays
  - Generating Random Samples from Distributions
- Comparison and Logical Operations
  - Comparison Operators
  - Logical Operators
  - Comparison Functions
  - Logical Functions
- Conclusion and Further Resources

## [**`Array Manipulation`**]()

- Reshaping Arrays
  - Reshaping 1D Arrays to 2D Arrays
  - Reshaping 2D Arrays to 1D Arrays
  - Reshaping to Higher Dimensions
- Flattening Arrays
  - Using `np.ravel()` to Flatten Arrays
  - Flattening Arrays with `np.flatten()`
- Stacking Arrays
  - Vertical Stacking with `np.vstack()`
  - Horizontal Stacking with `np.hstack()`
- Concatenating Arrays
  - Concatenating Arrays Using `np.concatenate()`
  - Specifying the Concatenation Axis
- Splitting Arrays
  - Splitting Arrays Vertically with `np.vsplit()`
  - Splitting Arrays Horizontally with `np.hsplit()`
- Tiling Arrays
  - Tiling Arrays with `np.tile()`
  - (Optional) Creating Grids with `np.meshgrid()`
- Summary and Conclusion

## [**`NumPy Sorting and Searching`**]()

- Sorting Arrays
  - `np.sort()`: Sorting Arrays in Ascending Order
  - `np.sort()` with `axis` Parameter: Sorting Along Specific Axes
  - In-place Sorting with `arr.sort()`
  - `np.argsort()`: Obtaining the Indices of Sorted Elements
  - Sorting in Descending Order
- Searching and Filtering Techniques
  - Boolean Indexing: Filtering Arrays Based on Conditions
  - Finding Indices of Elements Satisfying Conditions
  - Searching for Unique Elements with `np.unique()`
  - Set Operations: Intersection, Union, and Difference of Arrays
- (Optional) Sorting and Searching Performance
  - Time Complexity of Sorting and Searching Operations
  - Optimizing Sorting and Searching Performance
  - Comparison with Python's Built-in Sorting and Searching Functions
- Summary and Conclusion

## [**`Saving and Loading NumPy Objects`**]()

- Saving NumPy Arrays
  - Saving a Single NumPy Array with `np.save()`
  - Saving Multiple NumPy Arrays with `np.savez()`
  - Saving NumPy Arrays in Compressed Format with `np.savez_compressed()`
- Loading NumPy Arrays
  - Loading a Single NumPy Array with `np.load()`
  - Loading Multiple NumPy Arrays with `np.load()`
- Saving and Loading NumPy Arrays in Text Format
  - Saving NumPy Arrays in Text Format with `np.savetxt()`
  - Loading NumPy Arrays from Text Format with `np.loadtxt()`
- Saving and Loading NumPy Objects in CSV Format
  - Saving NumPy Objects in CSV Format with `np.savetxt()`
  - Loading NumPy Objects from CSV Format with `np.genfromtxt()`
- Best Practices and Tips for Saving and Loading NumPy Objects

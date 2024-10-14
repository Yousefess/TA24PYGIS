# Week 04

## [**`Introduction to File Handling and IO`**]()

- What are files?
  - Text Files
  - Binary Files
- Why is file handling important?
- Basic file handling operations
  - Open
  - Read
  - Write
  - Close
  - Demonstration of opening a file in Python
- The `open()` function and its modes
  - Description of different modes
  - Code examples showing how to open files in different modes
- Text files vs. binary files
  - Distinctions between handling text and binary files
  - Use cases for each type
- The importance of closing files and using `with` statements for safety
  - Explanation of why files need to be closed
  - Introduction to the `with` statement and context managers

## [**`Reading from Files`**]()

- Opening Files for Reading ('r' mode)
  - How to Open a File Using `open()`
- The `read()`, `readline()`, and `readlines()` Methods
  - The `read()` Method
  - The `readline()` Method
  - The `readlines()` Method
- Iterating Over File Objects Line by Line
  - Efficiency Benefits
- Working with File Paths (Absolute vs. Relative)
  - Understanding File Paths
  - Platform-Independent File Paths

## [**`Writing to Files`**]()

- Opening Files for Writing
  - Using `open()` to Create File Objects for Writing
  - The Difference Between Writing to a New File vs. an Existing File
- The `write()` Method
  - The Concept of Strings and How They Are Written to Files
- The `writelines()` Method
  - The Difference between `write()` and `writelines()`
- Truncating and Overwriting vs. Appending
  - Append to the End of a File with Mode `'a'`
  - Potential Risks of Overwriting Data and How to Prevent It
- File Buffering and Flushing
- Practical Examples
  - Example: Writing Log Data to a File
  - Example: Generating and Saving a Report

# Class

## [**`Introduction to Programming Paradigms`**]()

- Programming Paradigm Overview
  - What is a Programming Paradigm?
  - What a Programming Paradigm is Not
- Imperative Programming Paradigm
  - Procedural Programming
  - Object-Oriented Programming (OOP)
- Declarative Programming Paradigm
  - Functional Programming
  - Logic Programming
  - Database Querying
- Comparing Programming Paradigms
  - Imperative Programming
  - Declarative Programming
  - Declarative: Functional Programming
  - Imperative: Object-Oriented Programming
  - Guidelines on Choosing the Appropriate Paradigm


## [**`Introduction to Object-Oriented Programming`**]()

- Core Concepts of OOP
  - Classes and Objects
  - Attributes and Methods
  - Encapsulation
  - Inheritance
  - Polymorphism
  - Abstraction
- Advantages and Disadvantages of OOP


## [**`OOP in Python`**]()

- Basic Concepts of OOP in Python
  - What is a Class?
  - What is an Object?
  - Simple Class Creation Example in Python
  - Instantiating Objects from a Class
- Key Features of Python OOP
  - Encapsulation
  - Inheritance
  - Polymorphism
  - Abstraction
- Practical Example: Car Class
  - Instantiating an Object and Calling its Method:

## [**`Understanding Classes and Objects in Python`**]()

- Defining a Simple Class in Python
  - Introducing  Methods
  - Instantiate an Object from the Class
  - Clarifying the Necessity of Passing `obj` to Methods
- Instance Methods and the Use of `self`
  - Understanding `self`
  - Practical Code Examples Using `self`
  - Why `self` is Necessary
- The Role of `__init__` Method in Python Classes
  - Modifying the Car Class to Include the `__init__` Method
- Classes vs. Instances Attributes
  - Class Attributes
  - Instance Attributes
- Instantiating Objects
  - Creating Objects from a Class
  - Accessing Attributes and Invoking Methods
  - Maintaining Unique State

## [**`Object Initialization with the `__init__` Method`**]()

- Anatomy of the `__init__` Method
  - Basic Syntax and Structure
  - The Significance of the `self` Parameter
  - Parameters and Arguments in `__init__`
- Initializing Object Attributes with `__init__`

## [**`Understanding Inheritance in Python`**]()

- The Basics of Inheriting Classes
  - Adding and Overriding Methods
- The `super()` Function and Method Overriding

## [**`Types of Inheritance in Python`**]()

- Single Inheritance: Basics and Benefits
- Multilevel Inheritance: Advantages and Challenges
- Hierarchical Inheritance: Structure and Scenarios
- Multiple Inheritance: Concepts and Complexities (Optional)
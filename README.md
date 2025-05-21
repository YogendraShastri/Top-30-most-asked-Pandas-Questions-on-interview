# Top-30-most-asked-Pandas-Questions-on-interview
here is the list contains the most asked questions in pandas

### 1. What is Pandas in Python, and why is it used?
Pandas is an open-source Python library for data manipulation and analysis, built on NumPy. It provides data structures like Series (1D) and DataFrame (2D) for handling structured data efficiently.
It’s used for data cleaning, transformation, aggregation, and visualization in data science and analytics.

### 2. What is the difference between a Pandas Series and a DataFrame?
A Series is a one-dimensional labeled array, while a DataFrame is a two-dimensional tabular structure with labeled rows and columns. A DataFrame can be thought of as a collection of Series.
![image](https://github.com/user-attachments/assets/e3457c93-aad4-4fd2-b9b4-f3f90e7fcf13)

### 3. Why doesn’t DataFrame.shape have parenthesis?
The reason DataFrame.shape in pandas doesn't have parentheses (i.e., it's used as df.shape instead of df.shape()) is because it's an attribute, not a method.
Attributes like shape, columns, and index are lightweight, always available, and do not change any data or perform calculations.

### 4. How do you add a new column to a Pandas DataFrame?
Assign values to a new column name using df['new_column_name'] = value 
or 
use assign().
![image](https://github.com/user-attachments/assets/1861df97-7e79-4715-8756-ad0fda9cd60a)

### 5. How do you remove columns from a Pandas DataFrame?
Use drop(columns=['col_name']) with axis=1
 or 
del df['col_name']
![image](https://github.com/user-attachments/assets/02ee166e-75d0-458b-bc23-eed116d76aad)




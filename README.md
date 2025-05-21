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

### 6. What is the difference between loc and iloc?
* You use .loc[] when you want to access rows or columns by their labels (i.e., the actual names like employee_id, emp_name etc)
* You Use .iloc[] when you want to access rows or columns by their numerical position (starting from 0).
  
![image](https://github.com/user-attachments/assets/5850fbfb-4544-4d3f-855c-d6674b6baa16)

### 7. How do you merge two DataFrames in Pandas?
In Pandas, you can merge two DataFrames using the merge() function, which is similar to SQL joins. It allows combining rows based on one or more keys (columns)

![image](https://github.com/user-attachments/assets/36e43f90-8c6f-447b-9b13-71a280e3fe1d)

### 8. What is the difference between the .join() and .merge() methods in pandas?
merge(): In Pandas, the merge() function is used to combine rows of two DataFrames based on one or more key columns, similar to SQL joins.
join():In Pandas, the join() method is used to combine two DataFrames on their index (by default), though you can join on a column as well. It’s more convenient for joining based on the index.

### 9. What is the purpose of the apply() function in Pandas?
apply() applies a function along an axis (rows/columns) or to a Series.

![image](https://github.com/user-attachments/assets/3a2ff697-6a3c-452b-bccf-db4c21be7abf)

### 10. How do you rename columns or indexes in a DataFrame?
Use rename() with columns or index parameters to rename labels.

![image](https://github.com/user-attachments/assets/d1cfe41c-8541-4cc5-a526-fa8244a755f9)

![image](https://github.com/user-attachments/assets/41e04508-b6a9-4279-a618-709b2e45e285)





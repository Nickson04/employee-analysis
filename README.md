# Employee Data Analysis (My First Practice Project)

I am learning data analytics, and this is my first simple practice project.

## What this project does

This project explores and summarizes an employee dataset using Python and pandas:

- filtering and searching data
- creating new columns
- grouping and summarizing (groupby)
- charts

It also includes a small menu program ("Employee Manager") that can show all
employees, search by city, sort by salary, and add a new employee.

## How the project evolved

I started with a dataset that had only 4 columns (Name, Age, Salary, City).
Later I added 3 new columns (Salary_USD, Age_Group, Salary_Level). When I saved
those columns to the CSV file, option 4 (Add Employee) started giving an error,
because it only supplied the 4 original values for each new employee.

To fix this, I created the `add_derived_columns()` function. The CSV now stores
only the 4 original columns, and the function calculates the other 3 whenever
the data is loaded or a new employee is added. This way, every employee,
including new ones, gets all 7 columns.

## Files

- `employee-analysis.ipynb`: the analysis notebook
- `Employee.csv`: the dataset (fictional data)

## Tools

Python, pandas, NumPy, matplotlib, Jupyter Notebook

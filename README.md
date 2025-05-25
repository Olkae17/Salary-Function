### Employee Profile Data Processing ###




## Overview ## 

This project involves reading, processing, and exporting employee salary data using Python and R. It was developed as part of a data handling assignment using a provided dataset (`Total.csv`). The project demonstrates how to use dictionaries, functions, exception handling, and file operations to manage employee information.


## Files Included ##
- "Total" — Provided employee salary dataset  

- "Salary Function.ipynb" — Jupyter Notebook with all Python code, analysis, and R script to unzip and display employee profiles

- "Employee Profile.zip" — Sample zipped folder containing exported employee profile  

- README — This instruction file


## How to Run the Python Notebook ##

1. Open Jupyter Notebook 
   Launch Jupyter Notebook and open the file "Salary Function.ipynb".

2. Import and Preview the Data  
   The notebook reads from "Total" and previews the salary data.

3. Get an Employee’s Details  
   Use the following command in a cell:  
   get_employee_details("NATHANIEL FORD")
   
4. Export an Employee’s Profile to CSV and ZIP
   This creates a folder named Employee Profile, saves the employee data to a CSV file, and zips the folder:
   export_employee_to_csv("NATHANIEL FORD")

## How to Run the R Script ##

1. Make sure the "Employee Profile.zip" file exists in your working directory.

2. Open RStudio or any R environment.

3. Run the R script in the notebook

4. The script will unzip the folder and display the exported employee CSV file.


## Features Covered ##

-  Dynamic data filtering by name  

-  Error handling for missing names or invalid queries  

-  Data processing using Python dictionaries  

-  CSV export and ZIP creation using Python  

-  R script to unzip and display employee profile  

-  Clean, user-friendly output  


## Requirements ##

Python
- "pandas"

- "zipfile"

- "os"

R
- Base R (no additional packages needed)

## License ##
This project is for educational purposes and follows standard academic integrity guidelines.  

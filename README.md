# Task 19: Filter Dataset Records Using Pandas

## Project Overview
This project demonstrates how to filter dataset records using Python and the Pandas library. Boolean conditions are applied to retrieve relevant student records based on marks and attendance.

## Objective
To understand dataset filtering and learn how to select specific records using single and multiple conditions in Pandas.

## Technologies Used
- Python
- Pandas
- Jupyter Notebook
- VS Code

## Dataset Description
A sample student dataset containing 10 records is used. It includes the following columns:

- **Name:** Name of the student.
- **Marks:** Marks obtained by the student.
- **Attendance:** Attendance percentage.
- **Grade:** Grade assigned to the student.

## Filtering Operations

### 1. Filtering Marks
Selected students who scored more than 80 marks using the condition `Marks > 80`.

### 2. Filtering Attendance
Retrieved students whose attendance was greater than 80% using `Attendance > 80`.

### 3. Multiple Conditions Using AND
Selected students who scored more than 70 marks and had attendance above 80%. The `&` operator combines both conditions.

### 4. Multiple Conditions Using OR
Retrieved students who scored more than 90 marks or had attendance above 90%. The `|` operator selects records satisfying either condition.

## Key Concepts Learned
- Creating a Pandas DataFrame.
- Applying Boolean conditions.
- Filtering records using comparison operators.
- Combining multiple conditions using `&` and `|`.
- Displaying filtered DataFrames.
- Counting records after filtering.

## Results
The filtering operations successfully retrieved records matching the specified conditions. The number of records returned was calculated for each operation to verify the results.

## Conclusion
This project provided practical experience in filtering dataset records using Pandas. It demonstrated how Boolean conditions help retrieve relevant information and perform basic data analysis efficiently.

## Internship Details
**Organization:** Veda Technology  
**Track:** Artificial Intelligence and Machine Learning  
**Task:** 19 – Filter Dataset Records

## Repository Contents
- `filter_dataset_records.ipynb` — Python code and filtering results.
- `README.md` — Project overview, methodology, and conclusion.

# SQL Challenge

# Project Description 

## Part One: Data Modeling
- Create an Entity Relationship Diagram of the csv files using Quick DBD. 

## Part Two: Data Engineering
- Define columns, set the correct data types for each columns, set Primary Keys, set NOT NULL for columns as needed, and define column length to include all characters. 
- Import the CSV files into SQL.

## Part Three: Data Analysis
- List the employee number, last name, first name, sex, and salary of each employee.
- List the first name, last name, and hire date for the employees who were hired in 1986.
- List the manager of each department along with their department number, department name, employee number, last name, and first name.
- List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
- List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
- List each employee in the Sales department, including their employee number, last name, and first name.
- List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
- List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

# Software and Files
- SQL
- Quick DBD
- CSV files: departments, dept_emp, dept_manager, employees, salaries, and titles 

# Output/Analyses

## Part One: Data Modeling
- Created an Entity Relationship Diagram (ERD) using QuickDBD
![QuickDBD-export](https://user-images.githubusercontent.com/119909433/222546287-8858934a-dbd5-4b77-b060-5064e1f13d59.png)

## Part Two: Data Engineering
- Defined columns for each table, set them to the correct data types, identified primary keys, related other tables using foreign keys, used NOT NULL conditions for certain variables, and defined the lengths of string columns. 
<img width="771" alt="Screenshot 2023-03-02 at 2 40 42 PM" src="https://user-images.githubusercontent.com/119909433/222546718-d8b728a3-2578-4b8a-ac2c-cba9b0378aa7.png">
<img width="770" alt="Screenshot 2023-03-02 at 2 41 05 PM" src="https://user-images.githubusercontent.com/119909433/222546789-1e011e29-4b80-45ba-ad70-4529338843c8.png">

## Part Three: Data Analysis
- Listed the employee number, last name, first name, sex, and salary of each employee. 
<img width="766" alt="Screenshot 2023-03-02 at 2 43 04 PM" src="https://user-images.githubusercontent.com/119909433/222547225-ebd408d1-d9c0-4b9c-85db-40e8b3aa2c27.png">
<img width="703" alt="Screenshot 2023-03-02 at 2 43 14 PM" src="https://user-images.githubusercontent.com/119909433/222547257-d0de8f5a-174b-40c4-8e1e-085ab98ba818.png">

- Listed the first name, last name, and hire date for employees hired in 1986. 
<img width="769" alt="Screenshot 2023-03-02 at 2 44 15 PM" src="https://user-images.githubusercontent.com/119909433/222547439-f369eff9-cb70-449f-9e08-3906b0876923.png">
<img width="525" alt="Screenshot 2023-03-02 at 2 44 26 PM" src="https://user-images.githubusercontent.com/119909433/222547482-46d5f84f-dce8-4b75-80fd-306b146adabb.png">

- Listed the manager of each department along with their department number, department name, employee number, last name, and first name.
<img width="769" alt="Screenshot 2023-03-02 at 2 45 32 PM" src="https://user-images.githubusercontent.com/119909433/222547748-fcd582c9-46b1-4229-9b9c-212002cbb702.png">
<img width="749" alt="Screenshot 2023-03-02 at 2 45 46 PM" src="https://user-images.githubusercontent.com/119909433/222547795-44f495b5-963f-4566-aed9-084a8cbecf7f.png">

- Listed the department number for each employee along with that employee’s employee number, last name, first name, and department name.
<img width="769" alt="Screenshot 2023-03-02 at 2 47 02 PM" src="https://user-images.githubusercontent.com/119909433/222548172-94a6a1b7-57c6-4ca8-b5c6-5e77e476762b.png">
<img width="838" alt="Screenshot 2023-03-02 at 2 47 13 PM" src="https://user-images.githubusercontent.com/119909433/222548214-3f4ca563-3f5d-4b14-a49d-a8dc62ec3aad.png">

- Listed the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
<img width="760" alt="Screenshot 2023-03-02 at 2 47 58 PM" src="https://user-images.githubusercontent.com/119909433/222548365-195d1e63-a4de-4ea7-955b-21bc0e5701b0.png">
<img width="519" alt="Screenshot 2023-03-02 at 2 48 14 PM" src="https://user-images.githubusercontent.com/119909433/222548427-a0e7a3ec-b686-442c-8b42-05c9e2584080.png">

-Listed each employee in the Sales department, including their employee number, last name, and first name.
<img width="768" alt="Screenshot 2023-03-02 at 2 48 52 PM" src="https://user-images.githubusercontent.com/119909433/222548611-d019c26d-bee7-4e4c-a5a2-846420928da3.png">
<img width="591" alt="Screenshot 2023-03-02 at 2 49 02 PM" src="https://user-images.githubusercontent.com/119909433/222548656-878a6e47-293c-4dcb-8ab3-7f1853bf559a.png">

- Listed each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
<img width="755" alt="Screenshot 2023-03-02 at 2 49 34 PM" src="https://user-images.githubusercontent.com/119909433/222548801-58c29498-7802-48d5-b008-b4c8c7c809d5.png">
<img width="610" alt="Screenshot 2023-03-02 at 2 50 07 PM" src="https://user-images.githubusercontent.com/119909433/222548933-c5e3824e-7ac9-4ec2-b4bf-3fff7860f56c.png">

- Listed the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
<img width="698" alt="Screenshot 2023-03-02 at 2 50 40 PM" src="https://user-images.githubusercontent.com/119909433/222549056-84c6407e-42e9-4e56-8d07-9ceabec221eb.png">
<img width="396" alt="Screenshot 2023-03-02 at 2 51 12 PM" src="https://user-images.githubusercontent.com/119909433/222549180-9f9b011f-4798-4bd2-bd43-c46b91f9fa5f.png">



# Author 
-Brittany Wright github:brittanynicole7

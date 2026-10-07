# Project Overview
This is a python project talking about Student Management System as to how they are developed to show the use of programming concepts which involve scalars, lists, tuples, dictionaries, functions, and data management techniques which were used when adding, selecting, removing, updating and also viewing the student record.
# SCALARS
 
Section A deals with the use of scalar data types in Python. Scalars cannot be subdivided into smaller pieces for computation which means a value is seen as one item not a collection of items.
## THIS ARE THE SCALAR DATATYPES USED IN SECTION A:
### *String (Str)*
 
-Used to enter the student name at a time and also storing the grade at a time
 
example:
 
```python
name = input("Enter student name: ")
```
 
### *Integer (int)*
 
-used to enter the number of students as instructed by the user
 
-Has control as to howmany times the loop runs
 
example:
 
```python
num_students = int(input("Enter number of students: "))
```
 
### *Float (float) for student marks and averages.*
 
-Used to make sure that the number entered is exactly between 0-100
 
example:
 
```python
grade = float(input(f"Enter {subject} grade (0-100): "))
```
# SECTION B
Section B shows how lists and tuples were used for storing and collecting of data.
Lists are used to store multiple grades that can change during program execution.
Example:
 
```python
grades = [78, 65, 89]
```
Operations performed on lists include:
-Adding grades
 
-Updating grades
 
-Removing grades
 
-Calculating averages
Tuples are used to store information that cannot be modified or changed.
Example:
 
```python
subjects = ("Maths", "English", "Science")
```
This section demonstrates the differences between mutable (lists) and immutable (tuples) data structures.
# Section C: Dictionaries
 
Section C shows how nested dictionaries are used to store student records.
 
The dictionary structure allows each student to have multiple subjects and grades
Example:
 
```python
students = {
"Anesu": {
"Maths": [78, 85],
"English": [70, 82],
"Science": [90]
}
}
```
dictionaries were used to:
- Add student records
 
- Update grades
 
- Search for students
 
- Remove students
 
- View subject grades
 
- Display all records
reason for using dictionaries was the help to access the student's information quickly
# Example Input and Output
 
```text
===== STUDENT MANAGEMENT SYSTEM =====
1.Add Student
2.Update Student Grades
3.Remove Student
4.Search Student
5.View Subject Grades
6.Display All Students
7.Exit
Enter choice: 1
Enter student name: Anesu
Student added successfully.
```
# Assumptions
-Student names are unique.
 
-Grades are entered as numeric values.
 
-Subjects available are Maths, English, and Science.
# Limitations
-Data is stored only while the program is running.
 
-Records are not saved to a file or database.
 
-Duplicate student names are not allowed.
 
-Invalid user input may produce errors if validation is not implemented.
# Conclusion
This project demonstrates the practical application of Python programming concepts including scalars, lists, tuples, dictionaries, functions, and basic data management techniques. The Student Management System provides an organized way to manage student information and grades while ensuring understanding of programming structures.

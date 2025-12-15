# Student Grade Management System
 
A simple Python-based Student Grade Management System that allows users to manage student records efficiently. The program stores data in a text file and provides multiple operations through a menu-driven interface.
 
## Features
 
- Add new student records (first name, surname, subject, grade)
- Search for students by name
- Update existing student records
- Display all students grouped by subject
- Delete individual subject records or all records for a student
- View statistics per subject (average, highest, lowest grades)
- Data persistence using a text file
 
## File Structure
- main.py # Main program entry point
- menu.py # Banner and menu display
- student_actions.py # All user actions (add, search, update, delete, stats)
- student_data.py # Load and save student data
- colours.py # ANSI colour definitions
- students.txt # Text file storing student records

## How to Run
 
1. Make sure Python 3 is installed.
2. Open a terminal or command prompt in that folder.
3. Run the program by typing:
 python main.py

The program will start and display a menu with different options.

## Data Storage
Student records are stored in a text file called students.txt.
Each record is saved on a new line using the following format:
first_name,surname,subject,grade
Example:
amelie,brown,science,79

## Program Features
The system allows the user to:
- Add new student records
- Search for students by first name or surname
- Update existing student details
- Display all students grouped by subject
- Delete individual subject records or all records for a student
- View statistics such as average, highest, and lowest grades per subject
  
## Design Notes
The program uses a modular structure to keep the code organised and easy to understand.
Different files handle different responsibilities, such as menu display, data storage, and user actions.
Input validation and basic error handling are included to prevent invalid data entry.

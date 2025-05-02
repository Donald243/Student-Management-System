Student Management System

A Python-based application for managing student records, utilizing Tkinter for the GUI and PostgreSQL for database storage.

Features
- Create table for student records
- Insert new student data
- Update existing student data
- Delete student records
- Display student records in a treeview

Requirements
- Python 3.x
- Tkinter
- psycopg2 (PostgreSQL database adapter)
- PostgreSQL database (with studentdb database and postgres user)

Setup
1. Clone the repository
2. Install required packages: pip install psycopg2
3. Create a PostgreSQL database named "studentdb" with user "postgres" and password "admin123"
4. Run the application: python student_management_system.py

Usage
1. Launch the application
2. Create the student table by clicking "Create Table"
3. Insert new student data using the input fields and "Insert Data" button
4. Update existing student data by selecting a record and modifying the input fields, then clicking "Update Data"
5. Delete student records by selecting a record and clicking "Delete Data"

Contributing
Contributions are welcome! Please submit pull requests or issues on GitHub.

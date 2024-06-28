
# Tkinter GUI with MySQL Integration

This repository demonstrates how to connect a Tkinter GUI with a MySQL database. Follow the steps below to set up the database and run the application.

## Steps to Set Up the MySQL Database

1. **Open MySQL Workbench** and execute the following queries to set up the database:

    ```sql
    CREATE DATABASE vizag;
    USE vizag;
    CREATE TABLE record (
        stname CHAR(20),
        course CHAR(20),
        fee CHAR(20)
    );
    SELECT * FROM record;
    ```

## Steps to Run the Application

1. **Download the Jupyter Notebook code** from this repository.

2. **Run the Jupyter Notebook**.

3. **Provide Input in the GUI**:
    - Enter the student's name in the "Student Name" field.
    - Enter the course in the "Course" field.
    - Enter the fee in the "Fee" field.
    - Click the "Add" button to push the values to the database.

## Dependencies

Ensure you have the following dependencies installed:

- Python
- Tkinter


# Simple Student Management System

-----

## Overview of the Project

This project is a basic **command-line interface** written in Python for managing student records. It allows users to perform **CRUD** (Create, Read, Update, Delete) operations on student data, which includes personal details and academic grades. The data is stored in a list of dictionaries in memory for the duration of the program's execution.

-----

## Features

  * **Add New Student Data:** Users can enter a student's name, Date of Birth (DOB), admission number, blood group, and grades for five subjects (Calculus, EEE, Physics, English, Computer Science).
  * **View Student Details:** Users can retrieve and display a student's complete record by entering their unique admission number.
  * **Edit Student Details:** Users can modify personal details (name, DOB, admission number, blood group) for an existing student, identified by their admission number.
  * **Delete Student Details:** Users can permanently remove a student's record from the system using their admission number.
  * **Interactive Menu:** The application operates through a simple, numbered menu system.

-----

## Technologies/Tools Used

  * **Programming Language:** Python 3.x
  * **Data Structures:** Python Lists (for main storage) and Dictionaries (for individual student records and marks).
  * **Interface:** Command Line Interface / Console Input/Output.

-----

## Steps to Install & Run the Project

Since this is a single-file Python script with no external dependencies, the setup is straightforward:

1.  **Ensure Python is installed:** Make sure you have Python 3.x installed on your system.

2.  **Save the code:** Save the provided code into a file named, for example, `student_management.py`.

3.  **Run the script:** Open your terminal or command prompt, navigate to the directory where you saved the file, and execute the script using the Python interpreter:

    ```bash
    python student_management.py
    ```

4.  **Interact:** The main menu will appear, and you can start interacting with the system by picking an option.

-----

## Instructions for Testing

Follow these steps to test the main functionalities:

1.  **Start the program** (as described in the "Steps to Install & Run the Project" section).

2.  ### **Testing Option 1: Add New Student**

      * Select **`1`** from the main menu.
      * Enter sample data for a student (e.g., Name: `ABC`, Admission No: `A101`, Grades: all `100`).
      * Verify the success message: `-----DATA ENTERED SUCCESSFULLY-----`.

3.  ### **Testing Option 2: View Student Details**

      * Select **`2`** from the main menu.
      * Enter the admission number of the student you just added (e.g., `A101`).
      * **Expected Result:** The complete student dictionary is printed, confirming the data was saved.
      * Test a non-existent number (e.g., `Z999`).
      * **Expected Result:** Message `student not found`.

4.  ### **Testing Option 3: Edit Student Details**

      * Select **`3`** from the main menu and enter the admission number (e.g., `A101`).
      * Select **`1`** to edit the name. Enter a new name (e.g., `ABCD`).
      * The message `Details updated` should appear.
      * Use **Option 2** (View Student Details) to confirm the name has been updated to `AABCD`.

5.  ### **Testing Option 4: Delete Student Details**

      * Select **`4`** from the main menu.
      * Enter the admission number of the student (e.g., `A101`).
      * **Expected Result:** Message `Student data deleted`.
      * Use **Option 2** (View Student Details) and enter `A101` again.
      * **Expected Result:** Message `student not found`, confirming the data was removed.

6.  ### **Testing Option 5: Exit**

      * Select **`5`** from the main menu.
      * **Expected Result:** Message `!!Program terminated!!` and the program closes.
  
## Screenshots

   <img width="378" height="404" alt="image" src="https://github.com/user-attachments/assets/c774cddb-001a-4648-b151-333c9f4267f6" />
   <img width="606" height="403" alt="image" src="https://github.com/user-attachments/assets/94f50a2e-e4ee-4ed4-8482-459e35f0f68b" />
   <img width="1064" height="172" alt="image" src="https://github.com/user-attachments/assets/9a04c744-c63e-4cf3-85a6-45908f1b82d5" />
   <img width="684" height="78" alt="image" src="https://github.com/user-attachments/assets/2b0d28d6-1393-43d6-8d24-e65bde9e4fbb" />
   <img width="1071" height="81" alt="image" src="https://github.com/user-attachments/assets/c3718538-0cf9-4625-9306-a04a719d83dc" />





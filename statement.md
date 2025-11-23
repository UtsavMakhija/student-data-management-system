## 📝 Project Statement: Simple Student Management System (CLI)

-----

### 🎯 Problem Statement

The goal is to address the need for a **simple, accessible, and quick-to-use digital system** to store, retrieve, update, and delete basic academic and personal records for students. Currently, managing student data often relies on manual, scattered, or overly complex systems, leading to inefficiencies in tracking essential information like admission details, personal identifiers, and subject grades. This project provides a consolidated, in-memory solution for fundamental data management operations.

-----

### 🌐 Scope of the Project

The scope of this project is limited to providing core **CRUD (Create, Read, Update, Delete)** functionalities for student records within a **Command Line Interface (CLI)** environment.

  * **In-Memory Storage:** Data is stored in a Python list of dictionaries and **is not persisted** (saved) to a file or database upon program termination.
  * **Core Data Elements:** The system focuses on managing essential student attributes: Name, Date of Birth (DOB), Admission Number (used as a unique identifier), Blood Group, and specific subject grades (Calculus, EEE, Physics, English, Computer Science).
  * **Interaction:** User interaction is strictly menu-driven via console input.

-----

### 👤 Target Users

  * **Small Academic Departments or Tutors:** Individuals or groups needing to manage a small, temporary list of student data without the need for complex database infrastructure.
  * **Beginner Programmers or Learners:** Anyone seeking a clear, functional example of fundamental Python programming concepts, including lists, dictionaries, functions, and control flow (loops and conditionals).
  * **System Administrators (for basic data entry/testing):** Staff requiring a quick tool for data entry and manipulation during initial setup or testing phases.

-----

### ✨ High-Level Features

| Feature Category | Description |
| :--- | :--- |
| **Creation (C)** | **Add Student Data:** Capture and store a new student record, including personal details and five subject grades. |
| **Reading (R)** | **View Student Details:** Retrieve and display a complete student record using their unique Admission Number. |
| **Updating (U)** | **Edit Details:** Modify personal fields (Name, DOB, Admission Number, Blood Group) of an existing student record. |
| **Deletion (D)** | **Remove Student:** Permanently delete a student's entire record from the system using the Admission Number. |

<br>
Would you like to generate documentation for the specific functions (e.g., `add_data`, `edit_students`) used in the code?

# Student Record Management System

---

## Overview

This project is a simple, command-line interface (CLI) based **Student Record Management System** developed in Java. It allows users to perform basic **CRUD (Create, Read, Update, Delete)** operations on student records. The system uses an `ArrayList` to store `Student` objects in memory.

---

## Features

* **Add New Student:** Add a new student record with an auto-generated ID, name, and marks. Basic validation for marks (0-100) is included.
* **View All Students:** Display a list of all current student records.
* **Update Student Record:** Modify an existing student's name and/or marks by providing their ID.
* **Delete Student Record:** Remove a student record from the system by their ID.
* **Menu-Driven Interface:** Easy-to-use interactive menu for navigating through options.
* **Input Validation:** Handles invalid input types (e.g., non-numeric input when a number is expected).

---

## Technologies Used

* **Java:** The core programming language.
* **`ArrayList`:** Used for in-memory storage of student objects.
* **`Scanner`:** For handling user input from the console.

---

## How to Run

To run this application, you'll need the Java Development Kit (JDK) installed on your system.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/bharatjaiswal856/student-record-system.git
    cd student-record-system
    ```

2.  **Compile the Java Files:**
    Open your terminal or command prompt, navigate to the directory where you've saved `Student.java` and `StudentRecordManager.java`, and compile them:
    ```bash
    javac Student.java StudentRecordManager.java
    ```

3.  **Run the Application:**
    After successful compilation, run the main class:
    ```bash
    java StudentRecordManager
    ```

    The application will start, and you'll see the main menu in your console.

    ---

## Project Structure

* `Student.java`: Defines the `Student` class, representing a single student with properties like `id`, `name`, and `marks`. It includes a constructor, getters, setters, and an overridden `toString()` method for easy printing.
* `StudentRecordManager.java`: Contains the `main` method and implements the core logic for the Student Record Management System. It manages the `ArrayList` of `Student` objects and provides methods for adding, viewing, updating, and deleting records, along with the menu interface.

---

## Example Usage

Once you run the application, you'll be presented with a menu:

--- Student Record Management System ---
1. Add New Student
2. View All Students
3. Update Student Record
4. Delete Student Record
5. Exit
Enter your choice: 1

--- Add New Student ---
Enter Student Name: Bharat Jaiswal
Enter Student Marks (0-100): 88
Student added successfully with ID: 1

--- Student Record Management System ---
1. Add New Student
2. View All Students
3. Update Student Record
4. Delete Student Record
5. Exit
Enter your choice: 1

--- Add New Student ---
Enter Student Name: Shiva Jaiswal
Enter Student Marks (0-100): 90
Student added successfully with ID: 2

--- Student Record Management System ---
1. Add New Student
2. View All Students
3. Update Student Record
4. Delete Student Record
5. Exit
Enter your choice: 2

--- View All Students ---
Student { id=1, name='Bharat Jaiswal', marks=88 }
Student { id=2, name='Shiva Jaiswal', marks=90 }

--- Student Record Management System ---
1. Add New Student
2. View All Students
3. Update Student Record
4. Delete Student Record
5. Exit
Enter your choice: 5
Exiting application. Goodbye!

---

## Learnings and Takeaways

This project provided hands-on experience with:

* **Object-Oriented Programming (OOP) in Java:** Designing and implementing classes (`Student`) and managing objects.
* **Data Structures:** Practical application of `ArrayList` for dynamic data storage.
* **CLI Development:** Creating interactive console applications.
* **CRUD Operations:** Implementing fundamental data management functionalities.
* **Input Handling & Validation:** Using `Scanner` and basic error handling for user input.

---

### Author

* [Bharat Jaiswal](https://github.com/bharatjaiswal856/student-record-system)
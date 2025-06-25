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
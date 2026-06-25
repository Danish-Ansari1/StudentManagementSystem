# Student Management System

A simple, interactive Command-Line Interface (CLI) based application built in Python using Object-Oriented Programming (OOP) principles. This system allows users to manage student records efficiently by performing standard CRUD (Create, Read, Update, Delete) operations along with analytical insights like finding the top-performing student.

---

## 🚀 Features

* **Add Multiple Students:** Input and store detailed information for multiple students at once.
* **View All Records:** Display a well-formatted list of all active student records in the system.
* **Search by ID:** Instantly look up a specific student using their unique Student ID.
* **Update Marks:** Modify a student's marks seamlessly without changing other details.
* **Delete Records:** Remove a student completely from the system using their ID.
* **Identify Topper:** Calculate and display the details of the student with the highest marks.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Paradigm:** Object-Oriented Programming (OOP)

---

## 📋 Data Structure & Models

The application is structured into two core classes:

### 1. `Student` Class
Represents an individual student entity.
* **Attributes:** `student_id` (int), `name` (str), `age` (int), `marks` (float)
* **Methods:** `display()` (Prints individual student information)

### 2. `StudentManagementSystem` Class
Manages the collection of students stored dynamically inside an in-memory list (`self.store`).
* **Methods:** `add_student()`, `view_students()`, `search_student()`, `update_marks()`, `delete_student()`, `display_topper()`

---

## 🏃 How to Run the Application

### Prerequisites
Make sure you have Python installed on your system. You can check your version by running:
```bash
python --version
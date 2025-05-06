# Student Management System (Shell Script Project)

## Overview

This project is a **Student Management System** developed using Bash shell scripting. It provides a simple command-line interface for teachers and students to manage and view academic records. The system supports operations such as adding, deleting, updating, and listing students, along with authentication features.

## Features

### Teacher Functionalities:
- Login with password (`danger_round`)
- Add new student (up to 20 students)
- Delete student by roll number
- Update student name or marks (automatically recalculates grade and GPA)
- View list of:
  - All students (sorted by GPA in ascending or descending order)
  - Passing students (Grades A–D)
  - Failing students (Grade F)

### Student Functionalities:
- Login using registration number (roll number)
- View personal academic record (name, marks, grade, GPA)

## File Structure

- `Sms.sh` – Main script to launch the menu and handle user input.
- `Authentication.sh` – Script containing teacher and student logic.
- `student.txt` – Stores student records in the format:

# University-Management-System

A Python Tkinter-based University Management System that manages students, professors, and courses. Supports adding, searching, enrollment, and assignment with a simple GUI interface.

# Features

Add and manage students, professors, and courses.

Enroll students in courses and track credit hours.

Assign professors to courses.

Search by student/professor ID or course code.

View all registered students and professors.

Simple and user-friendly GUI interface.

# System Definition

Entities:

Student (ID, name, email, GPA, courses, credit hours)

Professor (ID, name, email, age, assigned courses)

Course (name, code, credits, students, professor)

Operations:

Add entities (students, professors, courses).

Enroll students in courses (with credit hours tracking).

Assign professors to courses.

Search for people by ID and courses by code.

Display lists of all students and professors.

# How it Works

Run the program → Tkinter GUI opens.

Use buttons to add students, professors, or courses.

Enroll students in courses or assign professors.

Search for details or view all records.

Data is displayed using Tkinter message boxes.

# Example Run

Add Student: Enter ID, name, email, and GPA → student stored.

Enroll Student: Enter student ID and course code → system updates credit hours.

Search Course: Enter course code → displays course details, professor, and enrolled students.

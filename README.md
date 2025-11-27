# Student Record Management System – Java Lab Assignment 5

A Java-based Student Record Management System that demonstrates **Object-Oriented Programming, File Handling, Exception Handling, Multithreading, and Java Collections**.

This project fulfills the complete requirements of **Java Lab Assignment 5** given by K.R. Mangalam University.

---

## ✅ Features

---

## ✅ Object-Oriented Programming (OOP)

- **Abstract class Person**
- **Inheritance (Student extends Person)**
- **Interface (RecordActions) implemented by StudentManager**
- **Encapsulation** with private fields and getters/setters
- **Modular structure** with multiple classes

---

## ✅ Student Operations

- Add a new student  
- Update existing student details  
- Delete student by name  
- Search student by name  
- View all students  
- Sort students by marks (Descending)  
- Validations for duplicate roll numbers  

---

## ✅ Exception Handling

- Custom exception: **StudentNotFoundException**
- Handles:
  - Invalid marks
  - Empty fields
  - Invalid roll number
  - Missing student on delete/search

---

## ✅ File Handling (Persistent Storage)

- Uses **BufferedReader** and **BufferedWriter**
- Automatically loads data from `students.txt`
- Saves updated data back to the file at exit

---

## ✅ Multithreading (Loading Simulation)

- Loader class implements **Runnable**
- Displays loading animation during:
  - Adding a student
  - Saving records

---

## ✅ Java Collections

- Stores student records in:
  - `List<Student>`
  - `Map<String, Student>` (rollNo → Student mapping)
- Uses **Comparator** for sorting
- Uses **Iterator** for displaying records



  

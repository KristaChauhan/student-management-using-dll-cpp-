# Doubly Linked List – Student Management System

## Overview
This project is a C++ implementation of a **Student Management System** using a **Doubly Linked List** data structure. It provides an efficient way to manage student records with support for insertion, deletion, searching, and traversal operations in both forward and backward directions. The project is designed to help understand the practical use of doubly linked lists in real-world applications.

---

## Features

### 1. Insertion Operations
- Insert a student record at the beginning of the list
- Insert a student record at the end of the list
- Insert a student record after a specified position

### 2. Deletion Operations
- Delete the first student record
- Delete the last student record
- Delete a student record after a specified position

### 3. Display Operations
- Display all student records from beginning to end
- Display all student records from end to beginning

### 4. Search Operation
- Search for a student record using a unique student ID

### 5. Demo Mode
- Automatically inserts predefined student records for testing and demonstration purposes

### 6. Error Handling
- Handles invalid inputs and edge cases such as empty lists and invalid positions

---

## Data Structure Used

The system uses a **Doubly Linked List**, where each node represents a student and contains the following fields:

- Student ID (unique identifier)
- Name
- Age
- Department
- GPA
- Pointer to the previous node
- Pointer to the next node

This structure allows efficient traversal in both directions and flexible insertion and deletion operations.

---

## Program Design

The program follows a **menu-driven approach**, allowing users to interactively choose operations such as inserting, deleting, searching, and displaying student records.

---

## Code Structure

### Key Functions
- `createStudent()` – Creates a new student node with provided details
- `insertAtBeginning()` – Inserts a node at the beginning of the list
- `insertAtEnd()` – Inserts a node at the end of the list
- `insertAfter()` – Inserts a node after a specified position
- `deleteFirst()` – Deletes the first node in the list
- `deleteLast()` – Deletes the last node in the list
- `deleteAfter()` – Deletes a node after a specified position
- `displayForward()` – Displays all nodes from start to end
- `displayBackward()` – Displays all nodes from end to start
- `searchNode()` – Searches for a student using student ID
- `addDemoStudents()` – Adds predefined student records to the list

---

## Example Usage

### Adding a Student
1. Select an insertion option from the menu
2. Enter student details such as ID, name, age, department, and GPA
3. The record is added to the list at the selected position

### Deleting a Student
1. Select a deletion option from the menu
2. Follow the prompts to remove the desired record

### Searching for a Student
1. Choose the search option from the menu
2. Enter the student ID to retrieve the record

### Displaying Records
- Use display options to view student records in forward or reverse order

---

## How to Compile and Run

```bash
g++ main.cpp -o student_management
./student_management

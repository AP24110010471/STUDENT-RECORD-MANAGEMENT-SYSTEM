# Student Management System (C Program)

A file-based Student Management System written in C.  
Supports multiple user roles (Admin, Staff, Guest) with authentication and permission-based access.

This program uses:
- File handling for permanent storage
- Role-based login system (admin, staff, guest)
- CRUD operations for students
- Temporary helper files for update and delete operations
- Simple text-based database

---

## Features

### Login System
| Role  | Add | Display | Search | Update | Delete | Logout |
|-------|:---:|:--------:|:-------:|:--------:|:-------:|:--------:|
| Admin | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Staff | ✔ | ✔ | ✔ | ✔ | ✖ | ✔ |
| Guest | ✖ | ✔ | ✔ | ✖ | ✖ | ✔ |

---

## Student Data Structure (students.txt)

Each student record is stored in the format:

roll name mark

makefile
Copy code

Example:

1 John 78.5
2 Maya 88.0

yaml
Copy code

---

## Credential Structure (credentials.txt)

Format:

username password role

makefile
Copy code

Example:

admin admin123 admin
staff staff123 staff
guest guest123 guest

yaml
Copy code

---

## Project File Structure

Student-Management/
├── main.c
├── students.txt
├── credentials.txt
└── README.md

yaml
Copy code

---

## Menu Overview

### Admin Menu
Add Student

Display Students

Search Student

Update Student

Delete Student

Logout

shell
Copy code

### Staff Menu
Add Student

Display Students

Search Student

Update Student

Logout

shell
Copy code

### Guest Menu
Display Students

Search Student

Logout

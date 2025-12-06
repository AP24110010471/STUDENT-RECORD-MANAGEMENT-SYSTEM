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



Example:

1 John 78.5
2 Maya 88.0


---

## Credential Structure (credentials.txt)

Format:

username password role


Example:

admin admin123 admin
staff staff123 staff
guest guest123 guest



---

## Project File Structure

Student-Management/
├── main.c
├── students.txt
├── credentials.txt
└── README.md


---

## Menu Overview

### Admin Menu
Add Student

Display Students

Search Student

Update Student

Delete Student

Logout


### Staff Menu
Add Student

Display Students

Search Student

Update Student

Logout


### Guest Menu
Display Students

Search Student

Logout

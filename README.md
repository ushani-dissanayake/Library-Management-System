# 📚 Library Management System

### Web-Based Library Management System using PHP & MySQL

The Library Management System is a web-based application developed to simplify common library operations and provide separate functionality for **librarians and members**.

The system supports book management, member registration, book requests, borrowing-related operations, and account management through a structured web interface.

---

## 🚀 Key Features

### 👨‍💼 Librarian Functions
- Librarian authentication
- Add and manage books
- Update book information and available copies
- Delete books
- Review pending member registrations
- Review pending book requests
- Manage member-related library operations

### 👤 Member Functions
- Member registration and login
- Browse available books
- Request books
- View personal book information
- Manage account-related information

---

## 🛠️ Technologies Used

### Frontend
`HTML` `CSS`

### Backend
`PHP`

### Database
`MySQL`

### Development Environment
`XAMPP / Local Web Server`

---

## 📂 Project Structure

```text
Library-Management-System/
│
├── css/
│   └── Application styles
│
├── img/
│   └── Interface assets
│
├── librarian/
│   └── Librarian-side functionality
│
├── member/
│   └── Member-side functionality
│
├── DATABASE FILE/
│   └── librarygh.sql
│
├── db_connect.php
├── header.php
├── index.php
├── logout.php
├── message_display.php
└── verify_logged_out.php

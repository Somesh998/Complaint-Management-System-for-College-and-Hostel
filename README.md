# 🎓 Complaint Management System for College and Hostel

A web-based Complaint Management System that allows students to register complaints related to college and hostel facilities, while administrators can efficiently manage, track, and resolve them.

##  Project Overview

The Complaint Management System is designed to simplify the process of reporting and resolving complaints within a college campus. Students can submit complaints regarding hostel facilities, classrooms, laboratories, Wi-Fi, cleanliness, electricity, water supply, and other campus-related issues.

The system enables administrators to review complaints, update their status, assign priorities, and notify students once the issue has been resolved.

## Features

## Student Module
- Student Registration
- Secure Login
- Submit Complaints
- Select Complaint Category
- View Complaint History
- Track Complaint Status
- Update Personal Profile

### 👨‍💼 Admin Module
- Admin Login
- View All Complaints
- Filter Complaints by Category
- Update Complaint Status
- Resolve Complaints
- Delete Invalid Complaints
- Manage Student Records
- Dashboard with Complaint Statistics

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- SQLite

### Tools
- VS Code
- Git
- GitHub

---

## Project Structure

```
Complaint-Management-System/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── student_dashboard.html
│   ├── admin_dashboard.html
│   └── complaint.html
│
├── database/
│   └── complaint.db
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
---

##  Complaint Workflow

```
Student Login
      │
      ▼
Submit Complaint
      │
      ▼
Complaint Stored in Database
      │
      ▼
Admin Reviews Complaint
      │
      ▼
Status Updated
      │
      ▼
Student Tracks Progress
      │
      ▼
Complaint Resolved
```

##  Database Tables

### Students

- Student ID
- Name
- Email
- Password
- Department
- Year

### Complaints

- Complaint ID
- Student ID
- Category
- Subject
- Description
- Date
- Status

### Admin

- Admin ID
- Username
- Password

##  Screenshots

Add screenshots of the following pages:

- Home Page
- Student Login
- Registration Page
- Student Dashboard
- Complaint Form
- Admin Dashboard
- Complaint List
- Complaint Status

---

##  Future Enhancements

- Email Notifications
- SMS Alerts
- Complaint Priority System
- AI-Based Complaint Categorization
- Mobile Application
- Role-Based Access Control
- Analytics Dashboard
- File Upload Support
- Complaint Search and Filter
- Dark Mode

---

##  Learning Outcomes

- Full Stack Web Development
- Flask Framework
- SQLite Database
- CRUD Operations
- User Authentication
- Database Integration
- Git and GitHub
- Responsive Web Design

---

## 👨‍💻 Author

**Somesh Kumar Kanamukkala**

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/kanamukkala-somesh-28917a36b/

---

## 📄 License

This project is developed for educational purposes and final-year academic submission.

Feel free to use, modify, and enhance it for learning.

**Thank you for visiting this project!**

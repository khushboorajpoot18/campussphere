# CampusSphere – College Management Platform

![React](https://img.shields.io/badge/Frontend-React.js-61DAFB?logo=react)
![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?logo=node.js)
![Express](https://img.shields.io/badge/Framework-Express.js-000000?logo=express)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?logo=mongodb)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)

CampusSphere is a full-stack MERN-based College Management Platform designed to simplify academic administration through secure role-based access. The platform enables administrators, faculty members, and students to efficiently manage academic activities, study resources, notices, and institutional data from a centralized dashboard.

---

## Features

### 👨‍💼 Administrator
- Manage faculty and student accounts
- Create and manage departments & branches
- Subject and semester management
- Upload notices and announcements
- Manage timetables
- Profile and account management

### 👨‍🏫 Faculty
- Upload study materials
- Manage assignments and notes
- View and search student details
- Upload timetables
- Access notices
- Update profile and credentials

### 👨‍🎓 Student
- View academic profile
- Access study materials
- View class timetable
- Download resources
- Check notices and announcements
- Update profile information

---

## Tech Stack

### Frontend
- React.js
- React Router
- Axios
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt

---

## Folder Structure

```
CampusSphere/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── media/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── utils/
│
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/khushboorajpoot18/campussphere.git
cd campussphere
```

### Install Dependencies

Backend

```bash
cd backend
npm install
```

Frontend

```bash
cd frontend
npm install
```

---

## Environment Variables

### Backend (.env)

```env
MONGODB_URI=your_mongodb_uri
PORT=4000
FRONTEND_API_LINK=http://localhost:3000
JWT_SECRET=your_secret_key

NODEMAILER_EMAIL=your_email
NODEMAILER_PASS=your_password
```

### Frontend (.env)

```env
REACT_APP_APILINK=http://localhost:4000/api
REACT_APP_MEDIA_LINK=http://localhost:4000/media
```

---

## Run Project

Backend

```bash
npm run dev
```

Frontend

```bash
npm start
```

---

## Default Admin Credentials

Generate an admin account using:

```bash
cd backend
npm run seed
```

Default Credentials

| Field | Value |
|-------|-------|
| Employee ID | 123456 |
| Email | admin@gmail.com |
| Password | admin123 |

---

## Authentication

- JWT Authentication
- Password Hashing using Bcrypt
- Protected Routes
- Role-Based Access Control

---

## Future Improvements

- Attendance Management
- Fee Management
- Analytics Dashboard
- Assignment Submission
- Email Notifications
- Mobile Responsive UI

---
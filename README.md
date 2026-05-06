# SMART CLASS360 — Smart Classroom Management Platform

SMART CLASS360 is a full-stack MERN web application designed to simplify and digitize school management operations. The platform helps administrators, teachers, and students manage academic workflows through a centralized dashboard.

---

## Features

### Admin
- Add/manage students and teachers
- Create classes and subjects
- Manage school records
- Monitor attendance and academic data

### Teacher
- Mark attendance
- Manage student performance
- Add marks and feedback
- View assigned classes and subjects

### Student
- View attendance
- Check marks and academic performance
- Access notices and announcements
- Track progress through dashboard analytics

---

## Tech Stack

### Frontend
- React.js
- Material UI
- Redux Toolkit

### Backend
- Node.js
- Express.js

### Database
- MongoDB

---

## Project Structure

```bash
backend/
frontend/
```

- `frontend/` → React frontend application
- `backend/` → Express server and MongoDB APIs

---

## Installation

### Clone Repository

```bash
git clone https://github.com/ruskyy04/smart-class360.git
```

---

## Backend Setup

```bash
cd backend
npm install
```

Create `.env` inside backend folder:

```env
MONGO_URL=mongodb://127.0.0.1:27017/smartclass360
SECRET_KEY=mysecretkey
```

Start backend:

```bash
npm start
```

Backend runs on:

```bash
http://localhost:5000
```

---

## Frontend Setup

```bash
cd frontend
npm install
```

Create `.env` inside frontend folder:

```env
REACT_APP_BASE_URL=http://localhost:5000
```

Start frontend:

```bash
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

## Future Improvements

- Parent dashboard
- Fees management
- Notification system
- JWT authentication
- Analytics dashboard
- Mobile responsiveness improvements
- Dark mode support

---

## Purpose

The project was built to improve understanding of:
- Full-stack MERN development
- REST API integration
- Authentication and role-based dashboards
- MongoDB database management
- Frontend-backend communication

---

## Author

Developed and customized by Rishit Kaushik.

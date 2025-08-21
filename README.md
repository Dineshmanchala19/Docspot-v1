# DocSpot - Healthcare Management System 🎉🏥

[![React](https://img.shields.io/badge/Frontend-React-blue)](https://react.dev/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-green)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Framework-Express-lightgrey)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

**DocSpot** is a full-stack healthcare management system that provides seamless appointment booking, doctor onboarding, and powerful administrative tools.  
Built with **React (SPA frontend)**, **Node.js + Express (REST API backend)**, and **MongoDB (NoSQL database)**, the system follows a **scalable and modular architecture** designed for production-ready deployments. 🚀

---

## 📋 Core Features

- **Doctor Discovery & Booking 🌟** – Search and schedule appointments with verified doctors.  
- **Patient Dashboard 📅** – Manage upcoming appointments and medical interactions.  
- **Doctor Application Portal 👩‍⚕️** – Secure onboarding workflow with approval system.  
- **Role-Based Access Control (RBAC) 🔧** – Separate views for Admins, Doctors, and Patients.  
- **Admin Dashboard with Analytics 📊** – Monitor system activity, approve doctors, and manage users.  
- **JWT-based Authentication 🔒** – Secure session handling with JSON Web Tokens.  
- **Responsive UI 🌐** – Tailwind CSS ensures optimal rendering across devices.  

---

## 📸 Screenshots

### Home Page  
![Home Page](https://raw.githubusercontent.com/Dineshmanchala19/Docspot-v1/main/screenshots/home.png)

### User Dashboard  
![User Dashboard](https://raw.githubusercontent.com/Dineshmanchala19/Docspot-v1/main/screenshots/user-dashboard.png)

### My Appointments  
![My Appointments](https://raw.githubusercontent.com/Dineshmanchala19/Docspot-v1/main/screenshots/my-appointments.png)

### Find a Doctor  
![Find a Doctor](https://raw.githubusercontent.com/Dineshmanchala19/Docspot-v1/main/screenshots/find-doctor.png)

### Apply as Doctor  
![Apply as Doctor](https://raw.githubusercontent.com/Dineshmanchala19/Docspot-v1/main/screenshots/apply-doctor.png)

### Admin Dashboard  
![Admin Dashboard](https://raw.githubusercontent.com/Dineshmanchala19/Docspot-v1/main/screenshots/admin-dashboard.png)

### User Management (Admin)  
![Users Managed by Admin](https://raw.githubusercontent.com/Dineshmanchala19/Docspot-v1/main/screenshots/usermang.png)

### Doctor Approval Workflow  
![Doctor Approval](https://raw.githubusercontent.com/Dineshmanchala19/Docspot-v1/main/screenshots/appt.png)

## 🛠 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Dineshmanchala19/Docspot-v1.git
cd Docspot-v1
2. Install Dependencies
```
```bash
Frontend (React):
cd frontend
npm install
Backend (Node.js / Express):
```
```bash
cd backend
npm install
3. Configure MongoDB
Install MongoDB locally or create a cluster using MongoDB Atlas.
Update your MongoDB connection string inside:
backend/config/connectToDB.js
```
```bash
4. Environment Variables
Create a .env file inside the backend directory:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

```bash
6. Run the Application
Start backend server:
cd backend
npm start
Start frontend app:
cd frontend
npm start
```
```bash
🎮 Usage Guide
Open http://localhost:3000 in your browser.

Register or log in as:

Patient: Book and manage appointments

Doctor: Apply for verification and manage consultations

Admin: Manage users, approve doctors, and view analytics

Use the Admin Panel for real-time oversight and approvals.
```
```bash
📜 License

This project is licensed under the MIT License
```

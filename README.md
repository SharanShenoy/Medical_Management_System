Got it! Here’s your updated README with badges added at the top for React, Flask, SQLite, and MIT License:

```markdown
# 🏥 Medical Management System

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)  
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)  
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)  
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)  

A **Medical Management System** built using **React (Frontend)** and **Flask (Backend)** with a **SQLite database** pre-populated with demo data.  
This project is designed to showcase management of **elder users, healthcare professionals, caregivers, emergency responders, patient information, and reminders**.

---

## ✨ Features

- **Frontend (React):**
  - Dashboard and navigation with React Router
  - Separate pages for each data category (Elders, Professionals, Caregivers, etc.)
  - Bootstrap Icons integration for a clean UI
  - Reminders and notifications displayed dynamically

- **Backend (Flask + SQLite):**
  - REST API endpoints for all data tables
  - Pre-generated demo data stored in `eldercare.db`
  - CORS enabled for frontend-backend communication

- **Demo Mode:**
  - Uses **generated data** in the database (no login system required for demo)

---

## 🛠️ Tech Stack

### Frontend
- **React.js**
- **React Router**
- **Bootstrap Icons**

### Backend
- **Flask (Python)**
- **SQLite3**

---

## 📂 Project Structure

```

medical-management-system/
├── backend/
│   ├── app.py              # Flask API
│   ├── eldercare.db        # SQLite database with demo data
│
├── frontend/
│   ├── src/
│   │   ├── App.js          # Main Router
│   │   ├── Dashboard.js
│   │   ├── elderUsers.js
│   │   ├── HealthcareProfessionals.js
│   │   ├── Caregivers.js
│   │   ├── EmergencyResponders.js
│   │   ├── PatientInformation.js
│   │   ├── Reminders.js
│   │   ├── EditDatabase.js
│   │   └── login.js
│   └── package.json

````

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/SharanShenoy/medical-management-system.git
cd medical-management-system
````

---

### 2. Backend Setup

```bash
cd backend
# Install dependencies
pip install flask flask-cors sqlite3

# Run Flask server
python app.py
```

Backend will run at: `http://127.0.0.1:5000`

---

### 3. Frontend Setup

```bash
cd frontend
# Install dependencies
npm install
# Start React dev server
npm start
```

Frontend will run at: `http://localhost:3000`

---

## 🖼️ Screenshots (Demo)

### Dashboard

![Dashboard](https://via.placeholder.com/800x400.png?text=Dashboard+Preview)

### Elder Users Page

![Elder Users](https://via.placeholder.com/800x400.png?text=Elder+Users+Page)

---

## 🌐 API Endpoints

| Endpoint                        | Description                    |
| ------------------------------- | ------------------------------ |
| `/api/elder-users`              | Fetch all elder users          |
| `/api/healthcare-professionals` | Fetch healthcare professionals |
| `/api/caregivers`               | Fetch caregivers               |
| `/api/emergency-responders`     | Fetch emergency responders     |
| `/api/patient-information`      | Fetch patient information      |
| `/api/reminders`                | Fetch reminders for demo       |

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use it for learning and demos.

---

## 👨‍💻 Author

* [Sharan Shenoy](https://github.com/SharanShenoy)

---

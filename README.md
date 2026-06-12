# 🚀 Major Project 2 — Full Stack Web Application

![Stack](https://img.shields.io/badge/Stack-MERN-61DAFB?style=flat-square&logo=react)
![Language](https://img.shields.io/badge/Language-JavaScript-yellow?style=flat-square&logo=javascript)
![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

> A full-stack web application with a dedicated backend API, responsive frontend, and an admin dashboard — built with JavaScript (Node.js + React).

---

## 📁 Project Structure

```
Major-Project2/
│
├── backend/          # Node.js + Express REST API server
├── frontend/         # React.js client-side application
└── dashboard-app/    # Admin dashboard panel
```

---

## ✨ Features

- 🔐 User Authentication (Register / Login)
- 📦 RESTful API with Express.js
- 🗄️ MongoDB Database Integration
- 🖥️ Responsive Frontend with React
- 📊 Admin Dashboard for data management
- 🌐 Full-stack communication via REST API

---

## 🛠️ Tech Stack

### Backend
| Technology | Purpose |
|------------|---------|
| Node.js | Runtime environment |
| Express.js | Web framework |
| MongoDB | Database |
| Mongoose | ODM for MongoDB |
| JWT | Authentication |
| bcrypt | Password hashing |

### Frontend
| Technology | Purpose |
|------------|---------|
| React.js | UI library |
| Axios | HTTP requests |
| React Router | Client-side routing |
| CSS / Tailwind | Styling |

### Dashboard
| Technology | Purpose |
|------------|---------|
| React.js | Dashboard UI |
| Chart.js / Recharts | Data visualization |

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)
- npm or yarn

---

### 1. Clone the Repository
```bash
git clone https://github.com/PrashantJ80/Major-Project2.git
cd Major-Project2
```

---

### 2. Setup Backend
```bash
cd backend
npm install
```

Create a `.env` file inside `/backend`:
```env
PORT=8080
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

Start the backend server:
```bash
npm start
```
> Server runs at `http://localhost:8080`

---

### 3. Setup Frontend
```bash
cd ../frontend
npm install
npm start
```
> App runs at `http://localhost:3000`

---

### 4. Setup Dashboard
```bash
cd ../dashboard-app
npm install
npm start
```
> Dashboard runs at `http://localhost:3001`

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register new user |
| POST | `/api/auth/login` | Login user |
| GET | `/api/users` | Get all users (admin) |
| GET | `/api/data` | Fetch data |
| POST | `/api/data` | Create new entry |
| PUT | `/api/data/:id` | Update entry |
| DELETE | `/api/data/:id` | Delete entry |

---

## 📸 Screenshots

> *(Add screenshots here after deployment)*

---

## 🚀 Deployment

- **Backend:** Render / Railway
- **Frontend:** Vercel / Netlify
- **Database:** MongoDB Atlas

---

## 👨‍💻 Author

**Prashant Jadhav**
B.Tech — Artificial Intelligence & Data Science
K. K. Wagh Institute of Engineering Education & Research, Nashik

[![GitHub](https://img.shields.io/badge/GitHub-PrashantJ80-black?style=flat-square&logo=github)](https://github.com/PrashantJ80)


> 

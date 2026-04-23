# MediDrop — Medicine Donation App

> A full-stack MERN web application that connects medicine donors with people in need — promoting healthcare accessibility and reducing medicine waste.

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://expressjs.com)
[![Render](https://img.shields.io/badge/Deployed_on-Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com)

---

## 📌 About

MediDrop is a platform where users can:
-  **Donate** unused or leftover medicines
-  **Browse** available medicine donations
-  **Request** medicines they need
-  Help reduce medicine waste and support those in need

---

## 📦 Repositories

This project is split into two separate repositories:

| Part | Repository |
|------|-----------|
| 🖥️ **Frontend** | [mediFrontend](https://github.com/Vaishnavi-sapkal/mediFrontend) | 
| ⚙️ **Backend** | [mediBackend](https://github.com/Vaishnavi-sapkal/mediBackend) | 

---

## 🏗️ Architecture

```
MediDrop
├── mediFrontend/       → React.js UI
│   ├── Components
│   ├── Pages
│   └── Deployed on Render (Static Site)
│
└── mediBackend/        → Node.js + Express REST API
    ├── Routes
    ├── Models
    ├── Controllers
    └── Deployed on Render (Web Service)
            |
            ↓
      MongoDB Atlas (Database)
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js, JavaScript, CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas |
| Deployment | Render |

---

## 📸 Screenshots 
## Donors & Receivers Portal

| Home Page | Listings | Donation Form |
|---|---|---|
| ![Home](https://github.com/user-attachments/assets/7fecec1b-d110-4f04-9171-286bdda3e6e4) | ![Listings](https://github.com/user-attachments/assets/704dd0d1-443c-4cc6-860b-7868b3b5b753) | ![Donation](https://github.com/user-attachments/assets/40949487-f4c6-437d-8ad1-82b4c9d928b5) |

## Admin Portal

| Home page | Donation Requests | requests receives |
|---|---|---|
| ![Home](https://github.com/user-attachments/assets/8b80a0db-865f-4d8d-aac0-f5df49b3b20e) | ![Donation](https://github.com/user-attachments/assets/4d096991-7f18-4631-ae5b-c5f4dd037c4f) | ![receivers](https://github.com/user-attachments/assets/f28d864d-16db-4a06-912f-9194a72a6851) |

## 🚀 Running Locally

### 1. Clone both repos
```bash
git clone https://github.com/Vaishnavi-sapkal/mediFrontend.git
git clone https://github.com/Vaishnavi-sapkal/mediBackend.git
```

### 2. Start Backend
```bash
cd mediBackend
npm install
# Add MONGODB_URI in .env
node server.js
```

### 3. Start Frontend
```bash
cd mediFrontend
npm install
npm start
```

---

## 👩‍💻Author

**Vaishnavi Sapkal**
- 🌐 [Portfolio](https://vaishnavisapkal.netlify.app/)
- 💼 [LinkedIn](https://linkedin.com/in/vaishnavi-sapkal)
- 🐙 [GitHub](https://github.com/Vaishnavi-sapkal)

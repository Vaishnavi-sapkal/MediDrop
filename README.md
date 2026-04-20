# 💊 MediDrop — Medicine Collection & Donation App

> A full-stack MERN web application that connects medicine donors with people in need — promoting healthcare accessibility and reducing medicine waste.

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://expressjs.com)
[![Render](https://img.shields.io/badge/Deployed_on-Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com)

---

## 🌐 Live Demo

🔗 [Visit MediDrop](https://medifrontend.onrender.com)

---

## 📌 About

MediDrop is a platform where users can:
- 💊 **Donate** unused or leftover medicines
- 🔍 **Browse** available medicine donations
- 📩 **Request** medicines they need
- ♻️ Help reduce medicine waste and support those in need

---

## 📦 Repositories

This project is split into two separate repositories:

| Part | Repository | Live URL |
|------|-----------|----------|
| 🖥️ **Frontend** | [mediFrontend](https://github.com/Vaishnavi-sapkal/mediFrontend) | [medifrontend.onrender.com](https://medifrontend.onrender.com) |
| ⚙️ **Backend** | [mediBackend](https://github.com/Vaishnavi-sapkal/mediBackend) | [medibackend-au6d.onrender.com](https://medibackend-au6d.onrender.com) |

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

## 👩‍💻 Developer

**Vaishnavi Sapkal**
- 🌐 [Portfolio](#)
- 💼 [LinkedIn](https://linkedin.com/in/vaishnavi-sapkal)
- 🐙 [GitHub](https://github.com/Vaishnavi-sapkal)

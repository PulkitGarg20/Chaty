# Chaty 💬

**Chaty** is a real-time chat application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) with **Socket.IO** for bi-directional communication. It allows users to register, log in, and communicate instantly in a clean and responsive user interface.

---

## 🚀 Features

- 🔐 User Authentication (JWT-based)
- 👤 Register and Login with password encryption
- 💬 Real-time messaging using **Socket.IO**
- 📜 Chat history saved in **MongoDB**
- 🌐 Responsive and modern UI with **Tailwind CSS**
- 🔎 Search for users and initiate new chats
- 📲 Notifications for new messages

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Axios
- React Router DOM
- Context API

**Backend:**
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT Authentication
- Bcrypt.js for password hashing
- Socket.IO for real-time communication

---

## 📂 Folder Structure

chaty/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── config/
│ ├── middleware/
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── context/
│ │ ├── pages/
│ │ ├── App.js
│ │ └── index.js
└── README.md

yaml
Copy
Edit

---

## 🧑‍💻 Getting Started

### Prerequisites

- Node.js
- MongoDB (local or cloud-based)
- npm / yarn

### Backend Setup

```bash
cd backend
npm install
# Configure MongoDB URI and JWT_SECRET in .env
npm run dev

# Chaty 💬  
A Real-Time Chat Application using MERN Stack & Socket.io

## 📝 Description

**Chaty** is a real-time chat application that allows users to register, log in, and chat with other users instantly. Built using the MERN stack, it features a modern UI with authentication, user search, group and private chat functionality, and instant message delivery using Socket.io.

---

## 🚀 Features

- 🔐 User Authentication (Register/Login)
- 🔎 Search users to chat
- 💬 One-to-One & Group Chats
- 🟢 Real-time messaging using Socket.io
- 📄 Chat history saved in MongoDB
- ✅ JWT-based Authentication
- 🧑‍🤝‍🧑 Join or Create Group Chats
- 📱 Responsive UI

---

## 🛠️ Tech Stack

### Frontend:
- React.js
- Axios
- Context API
- Tailwind CSS or Chakra UI

### Backend:
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.io
- JWT (JSON Web Token)
- bcryptjs

---

## 📦 Installation

### Clone the repository:

```bash
git clone https://github.com/your-username/chaty.git
cd chaty
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` directory and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Start the backend server:

```bash
npm start
```

---

### Frontend Setup

```bash
cd frontend
npm install
```

Start the React frontend:

```bash
npm start
```

---

## 📁 Project Structure

```
chaty/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── src/
│   └── public/
```

---

## 🧪 Testing

You can test the app by:
1. Registering two users.
2. Logging in simultaneously in two different browser windows.
3. Starting a chat and testing real-time messaging.

---

## 🙋‍♂️ Author

**Pulkit Garg**  
[LinkedIn](#) | [GitHub](#)

---

## 📃 License

This project is licensed under the MIT License.

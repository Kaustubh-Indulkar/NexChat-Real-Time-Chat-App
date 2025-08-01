# 💬 MERN Real-Time Chat Application

A simple and fully functional real-time chat application built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)** and **Socket.IO**. This app allows multiple users to send and receive messages instantly through a shared chat interface.

---

## 📌 Table of Contents

- [✨ Features](#-features)
- [📦 Tech Stack](#-tech-stack)
- [🗂️ Folder Structure](#️-folder-structure)
- [⚙️ Setup Instructions](#️-setup-instructions)
- [🧪 Example Code Snippets](#-example-code-snippets)
- [🛠️ Known Limitations](#️-known-limitations)
- [🤝 Contributing](#-contributing)
- [📝 License](#-license)

---

## ✨ Features

- 📡 Real-time messaging using **Socket.IO**
- 👥 Users join with their name
- 🗨️ Live message updates across all clients
- 💾 Persistent chat data using **MongoDB**
- ⚛️ Minimal and intuitive React frontend
- 🔌 REST + WebSocket-based architecture

---

## 📦 Tech Stack

| Layer       | Technology                     |
|-------------|--------------------------------|
| Frontend    | React, Axios, Socket.IO Client |
| Backend     | Node.js, Express.js            |
| Database    | MongoDB, Mongoose              |
| Realtime    | Socket.IO                      |
| Utilities   | dotenv, cors, nodemon          |

---

## 🗂️ Folder Structure

```bash
mern-chat-app/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── App.js
│       ├── index.js
│       └── components/
├── server/                 # Express backend
│   ├── models/
│   │   └── Message.js
│   ├── index.js
│   └── .env
├── README.md
└── package.json

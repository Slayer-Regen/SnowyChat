# SnowyChat 🌨️

> A Real-Time Full-Stack Chat Application with Authentication, built using React, Node.js, MongoDB, and Socket.io.

---

## 📚 Project Description

**SnowyChat** is a real-time, full-stack chat application designed to allow users to register, login securely, and instantly exchange messages. It leverages the power of **WebSockets** for real-time communication and **JWT authentication** for secure user sessions.

Built with a modern tech stack (React + Node.js + MongoDB + Socket.io), SnowyChat provides a seamless and fast messaging experience, suitable for personal projects, hackathons, or expanding into a full-fledged chat product.

---

## 📊 What Real-World Problem It Solves

As a **college student**, SnowyChat solves:
- The need to **learn real-world full-stack development**, including backend APIs, database management, and frontend integration.
- Understanding **real-time applications** with WebSocket technology.
- Building production-ready **authentication flows** using JWT.
- Preparing for **real-world software engineering interviews** by working on scalable projects.

Also, it can be expanded to serve as a base for:
- Group chats
- Real-time notifications systems
- Team collaboration tools

---

## 🔄 How the Project Works

### 1. User Authentication
- New users can **register** and **login** securely.
- Backend uses **JWT tokens** to manage sessions.
- Protected routes ensure only authenticated users access chat features.

### 2. Real-Time Messaging
- Once logged in, users join a real-time chat room.
- **Socket.io** maintains a persistent connection between client and server.
- Messages are sent and received instantly without refreshing the page.

### 3. State Management
- **Zustand** manages global state (e.g., user session info, messages) simply and efficiently on the frontend.

### 4. Database
- **MongoDB** stores user information and chat history.
- Backend uses **Mongoose** for schema definition and database operations.

---

## 🛠️ Tech Stack Used

| Technology  | Purpose |
|-------------|---------|
| **Vite + React** | Frontend development (fast build & optimized UI) |
| **Tailwind CSS** | Styling the user interface |
| **Node.js + Express** | Backend server, APIs, WebSocket handling |
| **Socket.io** | Real-time, bidirectional event-based communication |
| **MongoDB** | NoSQL database for storing users and messages |
| **Zustand** | Lightweight state management in frontend |
| **JWT** | Authentication and session management |
| **Mongoose** | MongoDB object modeling for Node.js |

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
https://github.com/yourusername/snowychat.git
```

### 2. Backend Setup
```bash
cd backend
npm install
```
- Create a `.env` file with:
```env
PORT=your_port
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```
- Run the server:
```bash
npm run dev
```

### 3. Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### 4. Socket.io Connection
Both client and server establish a WebSocket connection on load.

---

## 📈 Features

- User Registration and Login
- JWT Authentication
- Real-time messaging using Socket.io
- Zustand for client-side state management
- MongoDB database integration
- Responsive design with Tailwind CSS
- Error handling and Toast notifications

---

## 🧬 Example Usage

1. Register a new account.
2. Login and connect to chat room.
3. Send and receive messages instantly.

---


# 💟️ SnowyChat: Where conversations flow, as fast as snowfall!

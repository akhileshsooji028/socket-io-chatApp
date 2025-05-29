# 🧠 Socket.IO Chat Application

This repository contains a simple real-time chat application using **Socket.IO**. It includes both a server and client:

- **Server:** Built with **Express.js** and **Socket.IO** to handle chat communication.
- **Client:** Built with **React.js** and **Socket.IO Client** to provide a user interface for joining rooms and chatting.

> 🔄 This is a **basic implementation** — there is no database, authentication, or local storage. It's purely a demonstration of how Socket.IO enables real-time communication through joining rooms and exchanging messages.

---

## 📁 Project Structure

    root/
    │
    ├── server/ # Express.js server with Socket.IO
    └── client/ # React.js client with Socket.IO client


---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/akhileshsooji028/socket-io-chatApp.git
cd socketio-chat-app
```

## Server

```bash
cd server
npm install
nodemon index.js
```

## Client

```bash
cd client
npm install
npm start
```

## 🔧 Features

Join a chat room by name and room id

Send and receive messages in real-time

Basic and clean UI for demonstration of socket IO


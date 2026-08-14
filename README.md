# 💬 Real-Time Chat Web Application

A full-stack **real-time chat application** built using the **MERN Stack and Socket.IO**, designed to provide fast, reliable, and seamless communication between users.

## 🚀 Features

* 🔐 Secure user authentication
* 💬 Real-time one-to-one messaging
* 👥 Private and group conversations
* ⌨️ Real-time typing indicators
* 🟢 Live online/offline user presence
* ⚡ Instant bi-directional communication using Socket.IO
* 🔒 Protected routes and access control
* 📱 Responsive and user-friendly interface
* 🚀 Optimized backend event handling for concurrent users

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js
* Socket.IO

### Database

* MongoDB

### Tools

* Git & GitHub
* Postman
* VS Code

## 🏗️ Architecture

The application follows a client-server architecture:

**React.js Client → Socket.IO → Node.js/Express Server → MongoDB**

Socket.IO enables real-time bi-directional communication between the client and server, allowing messages and user-status updates to be delivered instantly without repeatedly polling the server.

## ⚙️ Core Functionality

### Real-Time Messaging

Messages are transmitted instantly using Socket.IO, eliminating the delays associated with traditional REST-based messaging.

### Typing Indicators

Users can see when another participant is typing through real-time socket events.

### User Presence

The application tracks online/offline status and updates users in real time.

### Private & Group Chats

Users can communicate through individual conversations as well as group chats with controlled access.

### Authentication & Security

Authentication and authorization mechanisms ensure that users can access only the conversations and resources they are permitted to use.

## 📂 Project Structure

```text
Real-Time-Chat-App/
│
├── client/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   └── server.js
│
├── .env
├── package.json
└── README.md
```

## 🔧 Installation & Setup

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
cd Real-Time-Chat-App
```

### 2. Install Dependencies

For the backend:

```bash
cd server
npm install
```

For the frontend:

```bash
cd ../client
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the backend directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Add any additional environment variables required by your implementation.

### 4. Run the Application

Start the backend:

```bash
cd server
npm start
```

Start the frontend in another terminal:

```bash
cd client
npm start
```

The application should now be available locally.

## 📈 Key Learning Outcomes

Through this project, I gained practical experience in:

* Designing real-time, event-driven applications
* Implementing bi-directional communication with Socket.IO
* Managing concurrent user interactions
* Building secure authentication and authorization
* Designing scalable backend architectures
* Working with MongoDB for persistent data storage
* Optimizing real-time event handling

## 🔮 Future Enhancements

* 📎 File and image sharing
* 🎙️ Voice and video calling
* 🔔 Push notifications
* 📨 Message read receipts
* 🔍 Advanced message search
* 🗑️ Message editing and deletion
* 🌐 Deployment with scalable infrastructure

## 👨‍💻 Author

**Piyush Mandal**

Built as a personal project to explore **real-time communication, scalable backend architecture, and modern full-stack web development**.

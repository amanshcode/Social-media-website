# Social Media Website

A full-stack social media web application built using the MERN stack that allows users to connect, share posts, manage profiles, follow other users, and communicate through real-time messaging. The application focuses on delivering a seamless and interactive social networking experience with secure authentication and modern web technologies.

---

## 🚀 Features

- User Registration & Login
- Secure JWT Authentication
- Password Encryption using bcrypt
- Edit User Profile
- Upload Profile & Cover Images
- Create, Edit & Delete Posts
- Like & Unlike Posts
- Follow & Unfollow Users
- Personalized Feed
- Real-Time One-to-One Chat using Socket.IO
- Responsive User Interface
- RESTful API Architecture

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt

### Real-Time Communication
- Socket.IO

### Additional Packages
- Multer (Image Uploads)
- dotenv
- CORS

---

## 📂 Project Structure

```
├── client      # Frontend
├── server      # Backend API
├── socket      # Socket.IO Server
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/amanshcode/Social-media-website.git
```

### Install dependencies

Frontend

```bash
cd client
npm install
```

Backend

```bash
cd server
npm install
```

Socket Server

```bash
cd socket
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the `server` directory and configure the required environment variables.

Example:

```env
PORT=
MONGO_URL=
JWT_SECRET=
```

If the frontend uses environment variables, create a `.env` file inside the `client` directory as well.

---

## ▶️ Running the Project

Start Backend

```bash
cd server
npm start
```

Start Frontend

```bash
cd client
npm start
```

Start Socket Server

```bash
cd socket
npm start
```

---

## 📸 Screenshots

Add screenshots of:

- Login Page
- Home Feed
- User Profile
- Real-Time Chat
- Create Post

---

## 🔮 Future Improvements

- Post Comments
- Notifications
- Stories
- Group Chat
- Voice & Video Calling
- Search Functionality
- Dark Mode

---

## 📚 Learning Outcomes

This project demonstrates practical implementation of:

- MERN Stack Development
- REST API Design
- Authentication & Authorization
- Real-Time Communication using Socket.IO
- MongoDB Database Design
- State Management in React
- File Upload Handling
- Client-Server Architecture

---


This project is intended for educational and learning purposes.

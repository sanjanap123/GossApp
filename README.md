# Gossap - Real-Time Chat Application

Gossap is a real-time chat application built using the MERN stack. It allows users to communicate instantly through one-to-one and group chats with secure authentication and online user tracking.

## Features

- User Signup and Login Authentication
- Real-Time Messaging using Socket.IO
- One-to-One Chat
- Group Chat Functionality
- Online User Tracking
- Profile Picture Upload
- Secure Password Encryption using bcrypt
- JWT Authentication with Cookies
- Responsive User Interface

## Technologies Used

### Frontend
- React.js
- Vite
- Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Other Tools
- Socket.IO
- JWT Authentication
- bcrypt
- Cloudinary

## System Architecture

The application follows a client-server architecture:

- Frontend built using React handles user interaction
- Backend APIs are created using Express.js
- MongoDB stores user, message, and group data
- Socket.IO manages real-time communication between users

## Authentication Flow

- User registers with email and password
- Password is encrypted using bcrypt
- JWT token is generated on login
- Token is stored in cookies
- Protected routes verify the token before access

## How to Run

### Clone Repository
```bash
git clone <your-repo-link>
```

### Install Frontend Dependencies
```bash
cd frontend
npm install
npm run dev
```

### Install Backend Dependencies
```bash
cd backend
npm install
npm start
```

## Main Features Explanation

### Real-Time Messaging
Messages are sent instantly without page refresh using Socket.IO.

### Group Chats
Multiple users can join a room and chat together.

### Online User Tracking
Tracks active users using userId and socketId mapping.

### Secure Authentication
Uses JWT tokens and bcrypt for safe login.

## Project Learning

This project helped me understand:

- Full-stack development
- API creation
- Authentication systems
- Real-time communication
- Database management
- Socket programming
- Clean backend architecture

## Future Improvements

- Audio calling
- Video calling
- Message seen/delivered feature
- Push notifications
- Better encryption
- Mobile application version

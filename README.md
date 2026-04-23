# Project Proposal & Tracking System

A full-stack web application designed to streamline the project proposal process between students and faculty. It features real-time communication, progress tracking, and secure authentication.

## 🚀 Features

- **User Roles:** Separate portals and functionalities for Students and Faculty.
- **Project Proposals:** Students can submit project proposals, and faculty can review, approve, or reject them.
- **Progress Tracking:** Track the status and progress of approved projects.
- **Real-time Chat:** Integrated real-time messaging using Socket.io for approved project groups to communicate effectively.
- **Authentication:** Secure OTP-based authentication system for users.

## 💻 Tech Stack

**Frontend:**
- React 19
- Vite
- React Router DOM
- GSAP (for animations)
- Firebase (Integration)
- Socket.io Client
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB & Mongoose
- Socket.io (Real-time WebSockets)
- CORS

## 📁 Project Structure

- `/frontend/PROJECT_PROPOSAL` - Contains the Vite + React frontend application.
- `/backend` - Contains the Node.js + Express backend application.

## 🛠️ Prerequisites

- **Node.js** (v16+ recommended)
- **MongoDB** installed and running locally on the default port `27017`, or a cloud MongoDB instance.

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd Project_Proposal
   ```

2. **Backend Setup:**
   ```bash
   cd backend
   npm install
   ```
   - Ensure your local MongoDB is running (`mongodb://127.0.0.1:27017/projectDB`).
   - Start the backend server:
   ```bash
   node server.js
   ```
   *The backend server will run on `http://localhost:5000`.*

3. **Frontend Setup:**
   ```bash
   cd frontend/PROJECT_PROPOSAL
   npm install
   ```
   - Start the Vite development server:
   ```bash
   npm run dev
   ```

## 📜 License

This project is open-source and available under the MIT License.

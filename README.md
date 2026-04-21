# 🏥 HealthTech (Zenith Health)

AI-powered affordable health & fitness monitoring platform using **Computer Vision + Emotion Detection + Smart Analytics + AI Coaching**.

> Built for hackathons, startup demos, and scalable SaaS deployment.

---

# 🚀 Overview

HealthTech (Zenith Health) is a modern web platform that helps users monitor their physical and mental wellness using only a webcam/device camera.

Unlike expensive wearables, our system uses **AI-based posture tracking, movement analysis, facial emotion detection, health scoring, analytics dashboards, and AI chatbot coaching**.

### 🎯 Core Mission

Make preventive healthcare and fitness tracking:

- Affordable  
- Accessible  
- Smart  
- Real-time  
- Personalized  

---

# ✨ Key Features

## 🧍 Physical Fitness Tracking

- Real-time pose detection
- Exercise rep counting
- Form accuracy detection
- Posture correction alerts
- Tempo / movement speed tracking
- Workout summaries

## 😊 Emotion & Mood Detection

- Webcam-based emotion recognition
- Detects:
  - Happy
  - Sad
  - Neutral
  - Angry
  - Fearful
  - Surprised

## 📊 Smart Health Analytics

- Overall Health Score
- Risk Score
- Fitness Score
- Mood Score
- Weekly performance graphs
- Workout history
- Trend charts

## 🤖 AI Health Coach

- Chatbot powered guidance
- Exercise recommendations
- Motivation support
- Recovery suggestions
- Personalized advice based on health metrics

## 🔐 Authentication System

- Register / Login
- JWT authentication
- Protected routes
- Profile management

---

# 🧠 Problem We Solve

Most health monitoring systems require:

- Smartwatches
- Fitness bands
- Medical devices
- Expensive subscriptions

Our solution removes hardware dependency using **AI + Camera only**.

---

# 🏗️ Tech Stack

## Frontend

- React.js
- Vite
- React Router DOM
- CSS3
- Lucide React Icons

## Backend

- Node.js
- Express.js
- JWT Authentication
- REST API Architecture

## Database

- MongoDB
- Mongoose ODM

## AI / ML

- TensorFlow.js
- MoveNet Pose Detection
- face-api.js Emotion Recognition
- Gemini API (AI Chatbot)

---

# 📁 Project Structure

```bash
HealthTech/
│
├── Backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── utils/
│   │   └── server.js
│   └── package.json
│
├── Frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── lib/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
└── README.md
## ⚙️ Complete Installation Guide

Follow these steps to run the project locally.

---

# 📌 Prerequisites

Make sure these are installed on your system:

* **Node.js** (v18 or higher recommended)
* **npm** (comes with Node.js)
* **MongoDB Community Server** OR MongoDB Atlas connection string
* **Git**

Check versions:

```bash
node -v
npm -v
```

---

# 1️⃣ Clone Repository

```bash
git clone <your-repository-url>
cd HealthTech
```

---

# 2️⃣ Backend Setup

Move into backend folder:

```bash
cd Backend
```

Install dependencies:

```bash
npm install
```

Create `.env` file inside Backend folder:

```env
PORT=5000
NODE_ENV=development
MONGO_URI=mongodb://localhost:27017/healthtech
JWT_SECRET=your_super_secret_key
GEMINI_API_KEY=your_gemini_api_key
CLIENT_ORIGIN=http://localhost:5173
```

Run backend server:

```bash
npm run dev
```

Backend will run on:

```text
http://localhost:5000
```

---

# 3️⃣ Frontend Setup

Open new terminal:

```bash
cd HealthTech/Frontend
```

Install dependencies:

```bash
npm install
```

Run frontend:

```bash
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

# 4️⃣ Start MongoDB

If using local MongoDB:

```bash
mongod
```

If using MongoDB Atlas:

Use Atlas connection string in `.env`

Example:

```env
MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/healthtech
```

---

# 5️⃣ Open Application

Visit:

```text
http://localhost:5173
```

---

# 🔐 Demo Login

```text
Email: demo@healthtech.com
Password: 123456
```

---

# 🛠 Common Commands

## Backend

```bash
npm run dev       # Start backend with nodemon
npm start         # Production mode
```

## Frontend

```bash
npm run dev       # Start Vite server
npm run build     # Production build
npm run preview   # Preview build
```

---

# 🚨 Troubleshooting

## Port Already In Use

Change backend port in `.env`

```env
PORT=5001
```

## MongoDB Connection Error

* Ensure MongoDB service is running
* Check URI in `.env`

## CORS Error

Ensure:

```env
CLIENT_ORIGIN=http://localhost:5173
```

## Node Modules Error

Delete and reinstall:

```bash
rm -rf node_modules package-lock.json
npm install
```

---

# 📦 Production Build

Frontend:

```bash
cd Frontend
npm run build
```

Backend:

Deploy Node.js server normally.

---

# ✅ Final Setup Summary

Terminal 1:

```bash
cd Backend
npm run dev
```

Terminal 2:

```bash
cd Frontend
npm run dev
```

MongoDB Running.

Open:

```text
http://localhost:5173
```

---

# 🎉 Ready to Use

Your AI HealthTech project is now running successfully.


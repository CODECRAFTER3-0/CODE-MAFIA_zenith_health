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

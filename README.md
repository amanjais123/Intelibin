# ♻️ IntelliBin - AIoT Smart Waste Segregation & Monitoring System

IntelliBin is an AI-powered smart waste management ecosystem developed for Smart India Hackathon 2025. The system combines Artificial Intelligence, IoT, Edge Computing, and Web Technologies to automate waste segregation, monitor bin utilization in real time, and streamline waste collection operations for Urban Local Bodies.

Traditional waste collection systems rely on fixed schedules and manual waste segregation, resulting in overflowing bins, inefficient collection routes, increased operational costs, and poor recycling rates. IntelliBin addresses these challenges by introducing intelligent waste classification, real-time monitoring, and role-based dashboards for different stakeholders.

---

## 🚀 Project Repositories

### 🏛️ Municipal Corporation Dashboard

**Live Demo:** https://github.com/amanjais123/SIHmuniciple/tree/main/frontend
**Repository:** https://sih-municiple.vercel.app/

A centralized monitoring platform for municipal authorities that provides a city-wide view of all deployed smart bins. The dashboard enables administrators to:

* Monitor bin fill levels in real time.
* Track segregated waste statistics.
* Identify bins requiring immediate collection.
* Analyze operational data and collection efficiency.
* Manage complaints and public feedback.

---

### 🚛 Garbage Collector Dashboard

**Live Demo:** https://github.com/amanjais123/SIHcollection
**Repository:** https://sih-collection.vercel.app/

A dedicated operational dashboard for waste collection personnel.

Features include:

* View assigned collection tasks.
* Track bins requiring service.
* Monitor collection progress.
* Update collection status in real time.
* Improve route planning and field operations.

---

### 🌐 Public Portal

**Live Demo:** https://github.com/amanjais123/sihUSER1
**Repository:** https://sih-user.vercel.app/home

A citizen-facing platform designed to improve communication between residents and municipal authorities.

Features include:

* Location-based notices and announcements.
* Complaint registration and tracking.
* Feedback submission.
* Public awareness regarding waste management initiatives.

---

### 🤖 AI/ML Waste Classification Model

**Repository:** https://github.com/amanjais123/Intelibin-aiml

The AI module is responsible for classifying waste as biodegradable or non-biodegradable.

Key Highlights:

* Trained using TensorFlow.
* Optimized using TensorFlow Lite for edge deployment.
* Performs on-device inference directly on Raspberry Pi.
* Enables low-latency classification without cloud dependency.

---

Responsibilities:

* Detect waste insertion.
* Capture waste images.
* Run AI inference locally.
* Operate segregation mechanism.
* Measure real-time fill levels.
* Send telemetry data to the cloud.

---

## 🏗️ System Architecture

1. Camera captures waste image.
2. TensorFlow Lite model classifies the waste.
3. Raspberry Pi activates servo mechanism.
4. Waste is directed into the correct compartment.
5. Ultrasonic sensors monitor fill levels.
6. Bin data is transmitted to the cloud.
7. Municipal and collector dashboards receive real-time updates.
8. Citizens interact through the public portal.

---

## 🛠️ Technology Stack

### Hardware

* Raspberry Pi
* Camera Module
* Ultrasonic Sensor
* Servo Motors

### Artificial Intelligence

* TensorFlow
* TensorFlow Lite

### Backend

* Node.js
* Express.js

### Frontend

* React.js

### Database

* MongoDB

### Cloud & Deployment

* Linux
* GitHub

---

## 🎯 Key Features

* AI-based waste segregation
* Real-time bin monitoring
* Edge AI inference on Raspberry Pi
* Automated waste compartment selection
* Municipal monitoring dashboard
* Collector operations dashboard
* Citizen engagement portal
* Cloud-connected IoT infrastructure

---

## 🌍 Impact

* Reduces landfill contamination through automated segregation.
* Prevents bin overflow using real-time monitoring.
* Optimizes waste collection operations.
* Improves urban cleanliness and sanitation.
* Enhances recycling efficiency.
* Supports Smart City initiatives through data-driven waste management.

---

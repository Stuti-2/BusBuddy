# 🚍 BusBuddy – RTC Management System

**BusBuddy** is a real-time bus tracking and seat availability application designed to enhance public transport efficiency, transparency, and commuter safety.

---

## 🧠 Introduction

Public transport users often face challenges like unpredictable bus schedules, limited seat availability visibility, and lack of digital ticketing solutions. **BusBuddy** solves these with a cross-platform mobile app (Flutter), a powerful backend (Spring Boot), and real-time data sync (WebSocket).

---

## 🎯 Problem Statement & Objective

> The project aims to eliminate uncertainties in public transportation by:
- Providing live bus tracking
- Displaying seat availability in real-time
- Enabling emergency assistance
- Offering digital ticketing and feedback mechanisms

---

## 💻 Tech Stack

| Layer       | Technology               |
|-------------|---------------------------|
| Frontend    | Flutter                   |
| Backend     | Spring Boot   |
| Database    | PostgreSQL   |
| Version Control | Git & GitHub         |

---

## 🔑 Key Features

### 💺 Seat Availability Updates
- Drivers manually update seats per stop (0% to 100%)
- Passengers get live data instantly

### 📱 Cross-Platform App
- Single Flutter codebase for Android & iOS
- Intuitive UI for passengers and drivers

### 📷 QR Code Ticketing
- Generate and scan QR codes for contactless ticket validation
- Payment gateway integration

### 📢 Emergency & Notifications
- SOS alerts with live location
- Push notifications for delays or announcements

### 📝 Feedback System
- 3-tier feedback (Good, Average, Bad)
- Optional comment input

---

## 🔧 Architecture & Implementation

- **Modular architecture** with clear separation of concerns
- **REST APIs** for all standard operations (CRUD, login, booking)
- **WebSocket** for real-time seat and location sync
- **Redis caching** for scalable high-frequency data loads
- **JWT authentication** for user login and security
- **PostGIS** for geospatial queries (e.g., nearest stop)



## 🧑‍💻 Contributors

- Karra Ram Teja
- Stuti Paras Jain
- Pratima Gurnani
- Supervisor: Dr. Aman Sharma




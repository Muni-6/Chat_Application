# Messaging System

## Overview
This project implements a **real-time messaging system** using **WebSockets**, **Redis**, **JWT authentication**, and **MongoDB**. It supports **one-to-one messaging**, **group chats**, **offline messaging**, and **user authentication**.

## Features
- **WebSocket-based real-time messaging**
- **User authentication with JWT**
- **Message persistence with MongoDB**
- **Redis for caching and scalability**
- **Containerized deployment with Docker**

## Setup and Installation
### **1. Clone the Repository & Install Dependencies**
```sh
git clone <repo-url>
cd messaging-system
npm install
```

### **2. Start Backend & Frontend**
```sh
cd backend && npm run dev
cd frontend && npm run dev
```


## Deployment Using Docker
### **Run Containers**
```sh
docker-compose up -d
```

## Conclusion
This messaging system is **scalable**, **real-time**, and **secure**, ideal for chat applications with future enhancements like **encryption and cloud deployment**.


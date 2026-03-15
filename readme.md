# Ecommerce AWS Deployment Project

## 📌 Project Overview

This project is a **full-stack eCommerce application** deployed on **AWS**.
The backend is hosted on an **EC2 instance**, while the frontend is hosted using **Amazon S3 static hosting**.

The application allows users to browse products, manage their accounts, and perform typical eCommerce operations.

---

# 🚀 Tech Stack

### Frontend

* React.js
* JavaScript
* CSS
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt for password hashing

### Cloud & Deployment

* AWS EC2 → Backend hosting
* AWS S3 → Frontend hosting
* PM2 → Node.js process manager
* Nginx (optional) → Reverse proxy

---

# 📂 Project Structure

```
Ecommerce_AWS
│
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── server.js
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```
git clone https://github.com/Arijitmanna200/Ecommerce_AWS.git
cd Ecommerce_AWS
```

---

## 2️⃣ Backend Setup

```
cd backend
npm install
```

Create `.env` file

```
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend

```
npm start
```

or using **PM2**

```
pm2 start server.js
```

---

## 3️⃣ Frontend Setup

```
cd frontend
npm install
npm start
```

---

# ☁️ Deployment

### Backend

Deployed on **AWS EC2**

Steps:

1. SSH into EC2 instance
2. Install Node.js
3. Clone repository
4. Install dependencies
5. Run using PM2

### Frontend

Deployed using **AWS S3 Static Hosting**

Steps:

1. Build React app

```
npm run build
```

2. Upload `build` folder to S3 bucket
3. Enable static website hosting

---

# 🔐 Authentication Features

* User Registration
* User Login
* JWT Authentication
* Secure Password Hashing with bcrypt
* Protected API routes

---

# ✨ Features

* User authentication
* Product browsing
* Account management
* Cloud deployment using AWS
* REST API architecture

---

# 📸 Future Improvements

* Payment Gateway Integration
* Order Management System
* Admin Dashboard
* Product Reviews & Ratings
* Redis Caching

---

# 👨‍💻 Author

**Arijit Manna**
GitHub:
https://github.com/Arijitmanna200

**Shoban Sen**
GitHub:
https://github.com/Shobhansen

**Samarpita Mukherjee**
GitHub:
https://github.com/Samarpita15082003

**Santanu Halder**
GitHub:
https://github.com/Santanu-jpg

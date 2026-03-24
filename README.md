# 🚀 Express + MongoDB Demo 

A simple demo backend project using **Node.js**, **Express.js**, and **MongoDB** with basic authentication (JWT & Cookies).

---

## 📦 Features

* User Registration
* User Login (JWT Authentication)
* Protected Routes
* Cookie-based Authentication
* MongoDB Database Integration

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB
* JWT (jsonwebtoken)
* bcryptjs
* cookie-parser
* cors

---

## 📁 Project Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2️⃣ Install dependencies

```bash
npm install
```

---

### 3️⃣ Create `.env` file

Create a `.env` file in the root directory and add:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

### 4️⃣ Run the server

```bash
npm run dev
```

or

```bash
node index.js
```

---

## 🔐 API Endpoints

### 🟢 Register

```
POST /register
```

### 🔵 Login

```
POST /login
```

### 🟡 Get Profile (Protected)

```
GET /profile
```

---

## 🍪 Authentication

* Uses **JWT stored in HTTP-only cookies**
* Automatically sent with requests using `withCredentials: true`

---

## ⚙️ Git Setup (First Time)

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main
```

---

## 🔄 Update Code

```bash
git add .
git commit -m "update: your message"
git push
```

---

## 📌 Notes

* Make sure MongoDB is running or use MongoDB Atlas
* Do not share your `.env` file
* Add `.env` to `.gitignore`

---

## 📄 License

This project is for learning purposes.

---

## 👨‍💻 Author

Your Name

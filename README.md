# 📚 Library Management System (Dashboard)

![Node.js](https://img.shields.io/badge/Node.js-Express-green)
![EJS](https://img.shields.io/badge/View%20Engine-EJS-orange)
![Project](https://img.shields.io/badge/Type-Mini%20Project-blue)

A **Library Management System Dashboard** built using **Node.js, Express, and EJS**.  
This mini project allows users to manage books, issue/return them, and maintain library records through a clean and simple web interface.

---

## ✨ Project Overview

Manual library management is inefficient and prone to errors.  
This project provides a **dashboard-style web application** where books can be:

- Added to the library
- Issued to users
- Returned back to the library
- Deleted when no longer needed

The UI is rendered using **EJS templates**, making it dynamic and easy to extend.

---

## 🚀 Features

- 📖 Add new books
- 📋 View all books in a table
- 🔄 Issue books
- ✅ Return issued books
- ❌ Delete books
- 🟢 Live status update (Available / Issued)
- 🎨 Clean and modern dashboard UI

---

## 🛠️ Tech Stack

| Technology | Description |
|---------|-------------|
| Node.js | Runtime environment |
| Express.js | Backend framework |
| EJS | Templating engine |
| HTML & CSS | UI design |
| Body-Parser | Form data handling |

---

## 📂 Project Structure
```bash
library-management-system/
│
├── app.js # Main server file
├── package.json # Project metadata & dependencies
├── package-lock.json # Dependency lock file
│
├── views/
│ └── home.ejs # Dashboard UI (EJS template)
│
└── README.md # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/priyanshuparekh83-star/library-management-system.git
```
### 2️⃣ Navigate to the project folder
```bash
cd library-management-system
```
### 3️⃣ Install dependencies
```bash
npm install
```
### 4️⃣ Start the server
```bash
node app.js
```
### 5️⃣ Open in browser
```bash
http://localhost:3000
```

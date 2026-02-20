🛍️ ShopHub Admin Dashboard

A full-stack Admin Dashboard system with authentication, user management, product CRUD operations, and Active/Inactive status control using JSON Server.

🚀 Features

🔐 Authentication System

Login / Signup

Role-based access (Admin / User)

Inactive users blocked from login

LocalStorage session handling

👥 User Management (Admin Panel)

View all users

View user details

Delete users

Toggle Active / Inactive status

Status saved in API

📦 Product Management

Add new product

Edit product

Delete product

View product list

Image preview support

🎨 UI Features

Sidebar navigation

Section switching (Dashboard / Users / Products)

Responsive layout

Clean and modern UI

🛠️ Technologies Used

HTML5

CSS3

JavaScript (Vanilla JS)

JSON Server (Mock REST API)

LocalStorage

📂 Project Structure

project-folder/
│
├── index.html (User Home Page)
├── dashboard.html (Admin Dashboard)
├── auth.html (Login / Signup)
├── db.json (JSON Server Database)
└── README.md

⚙️ How To Run Locally

Install JSON Server

npm install -g json-server

Start Backend

json-server --watch db.json --port 3000

Backend runs on:
http://localhost:3000

Open Frontend

Open auth.html in your browser.

🔑 Default Admin (Example)

Add this inside db.json:

{
"id": 1,
"username": "admin",
"pass": "1234",
"age": 25,
"number": "9999999999",
"role": "admin",
"status": "active"
}

🔥 Future Improvements

JWT Authentication

Password encryption

Search & Filter

Pagination

React Version

Deployment (Render / Vercel)

Real Backend (Node.js + Express + MongoDB)

📌 Author

Developed by Rachit 🚀

📄 License

This project is for educational and portfolio purposes.

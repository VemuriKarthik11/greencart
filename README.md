# 🛒 GreenCart – Eco-Friendly E-Commerce Platform


GreenCart is a fully functional e-commerce platform developed using the **MERN stack** (MongoDB, Express.js, React, Node.js). It allows users to browse eco-friendly products, manage a cart, and place orders. Sellers can manage inventory through a secure dashboard.

> Built from scratch, this project demonstrates full-stack development, authentication, RESTful API design, and modern UI/UX practices.

---

## 🚀 Features

### 👤 User Features
- Browse products with filters and search
- View detailed product pages
- Add/remove items to/from cart
- Place orders and view past orders

### 🛍️ Seller Features
- Secure seller login
- Add/edit/delete products
- Manage product listings

### 🛡️ Tech Features
- JWT-based authentication
- Protected routes (middleware)
- Image upload via Cloudinary
- Responsive and mobile-friendly UI

---

## 🛠️ Tech Stack

### Frontend
- **React.js** – UI components and SPA
- **Tailwind CSS** – Modern styling
- **Axios** – API handling
- **React Router** – Routing

### Backend
- **Node.js + Express.js** – REST APIs and middleware
- **MongoDB + Mongoose** – NoSQL database
- **JWT** – Authentication
- **Cloudinary** – Product image storage

---

## 📁 Project Structure

greencart/
│
├── client/ # React frontend
│ ├── pages/
│ ├── components/
│ └── App.jsx
│
├── server/ # Express backend
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ └── server.js
│
├── .env
├── README.md
└── package.json

yaml
Copy
Edit

---

## 🧑‍💻 How to Run Locally

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/greencart.git
cd greencart
Set Up Environment Variables

Create .env files for both client and server:

server/.env

ini
Copy
Edit
MONGO_URI=your_mongodb_url
JWT_SECRET=your_jwt_secret
CLOUDINARY_API_KEY=your_key
CLOUDINARY_SECRET=your_secret
client/.env

ini
Copy
Edit
VITE_BASE_URL=http://localhost:5000
Install Dependencies

In both /client and /server folders:

bash
Copy
Edit
npm install
Run the App

bash
Copy
Edit
# Start backend
cd server
npm run server

# Start frontend
cd client
npm run dev
📌 Highlights
Clean, modular codebase with MVC structure

Fully responsive layout with Tailwind CSS

JWT-secured role-based access for seller and customer

Modern React patterns (hooks, context API)

🧠 What I Learned
Building scalable REST APIs with Express

State management and data flow in React

Secure authentication flow with JWT

Full deployment flow with Vercel + MongoDB Atlas

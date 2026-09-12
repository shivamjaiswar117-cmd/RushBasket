# 🛒 RushBasket – Grocery Delivery Project

RushBasket is a full-stack grocery delivery web application that allows users to browse grocery items, manage their cart, place orders, and make online payments.

The project also includes a separate admin panel for managing products and orders.

## 🚀 Live Demo

- **Frontend:** https://rush-basket-ten.vercel.app
- **Backend:** https://rush-basket-backend.vercel.app
- **Admin Panel:** Add your admin Vercel URL here

## ✨ Features

### 👤 User Features

- User registration and login
- Browse food products
- View product details
- Add items to cart
- Update cart quantities
- Remove items from cart
- Place orders
- Online payment using Stripe
- View order details
- Order verification

### 👨‍💼 Admin Features

- Admin login
- Add food products
- Upload product images
- View product list
- Manage products
- View customer orders
- Manage orders

### 🔐 Authentication & Security

- User authentication
- Password protection
- Authentication middleware
- Role-based access for admin functionality
- Environment variables for sensitive configuration

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- JavaScript
- CSS
- React Context API

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- REST APIs
- Authentication middleware

### Admin Panel

- React.js
- Vite
- JavaScript
- CSS

### Payment

- Stripe

### Deployment

- Vercel
- GitHub

## 📁 Project Structure

```text
RushBasket/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── page/
│   │   ├── assets/
│   │   ├── App.jsx
│   │   ├── CartContext.jsx
│   │   └── main.jsx
│   └── package.json
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── admin/
│   ├── src/
│   │   ├── components/
│   │   └── ...
│   └── package.json
│
└── README.md
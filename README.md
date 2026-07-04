<<<<<<< HEAD
# Gym Management System

A full-stack MERN (MongoDB, Express, React, Node.js) web application for managing gym memberships, admissions, user profiles, product store, and orders. This project is split into two main folders:
- `gym_backend` — Node.js/Express REST API
- `gym_frontend` — React web app (Vite + MUI)

## 🔗 Live Demo & Repository

- 🌐 **Live Site:** [https://gym-management-slff.vercel.app](https://gym-management-slff.vercel.app)  
- 📦 **GitHub:** [https://github.com/Abhirag05/Gym-Management](https://github.com/Abhirag05/Gym-Management)

## Features

### User Features
- **User Registration & Login:** Secure authentication, registration, and profile management.
- **Membership Plans:** Browse, select, and enroll in gym plans (Basic, Pro, Premium, Personal Training).
- **Personalized Dashboard:** View and update profile, admission details, and membership status.
- **Workout & Nutrition Plans:** Custom schedules and tips based on fitness goals.
- **Order Management:** Buy supplements and gym products from the store, manage cart, checkout, and view order history.
- **Responsive UI:** Modern, mobile-friendly interface using Material UI.

### Admin Features
- **Product Management:** Add, update, or delete gym products (with image upload).
- **User/Admission Management:** View and update user admissions, plans, and details.
- **Order Management:** View all orders placed by users.

---

## Tech Stack
- **Frontend:** React 19, Vite, Material UI, Axios, React Router, Framer Motion
- **Backend:** Node.js, Express 5, MongoDB (via Mongoose), JWT Auth, Multer (file upload), CORS
- **Dev Tools:** ESLint, Vercel (deploy), dotenv

---

## Project Structure

```
Internship_Project/
│
├── gym_backend/    # Express REST API
│   ├── index.js
│   ├── connection.js
│   ├── models/
│   ├── uploads/
│   └── ...
│
├── gym_frontend/  # React Vite App
│   ├── src/
│   ├── public/
│   ├── index.html
│   └── ...
│
└── README.md
```

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Abhirag05/Gym-Management.git
```

### 2. Setup Backend
```bash
cd gym_backend
npm install
# Create a .env file with your MongoDB URI:
# MONGO_URL=mongodb+srv://<username>:<password>@cluster.mongodb.net/gymdb
npm start
```
- The backend runs on **http://localhost:3004** by default.

### 3. Setup Frontend
```bash
cd ../gym_frontend
npm install
# Create a .env file with:
# VITE_BACKEND_URL=http://localhost:3004
npm run dev
```
- The frontend runs on **http://localhost:5173** by default.

---

## Environment Variables

### Backend (`gym_backend/.env`)
```
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Frontend (`gym_frontend/.env`)
```
VITE_BACKEND_URL=http://localhost:3004
```

---

## API Overview

- `POST   /register` — User registration
- `POST   /login` — User login
- `GET    /profile/:email` — Get user profile
- `PUT    /profile/:email` — Update user profile
- `POST   /admission` — New admission
- `GET    /getAdmissionByEmail/:email` — Get admission info
- `GET    /products` — List all products
- `POST   /products` — Add product (admin)
- `PUT    /products/:id` — Update product (admin)
- `DELETE /products/:id` — Delete product (admin)
- `POST   /cart` — Add to cart
- `GET    /getcart/:userId` — Get user cart
- `DELETE /removefromcart/:userId/:cartItemId` — Remove from cart
- `DELETE /clearcart/:userId` — Clear cart
- `POST   /checkout` — Place order
- `GET    /orders/:userId` — Get user orders
- `GET    /vieworders` — Get all orders (admin)

---

## License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

- [Abhirag](https://github.com/Abhirag05)  
- Internship Project — 2025

=======
# Project
This is my first project
>>>>>>> 751b2111644ef78844ec38e6ee5b2f5d0e7cb87a

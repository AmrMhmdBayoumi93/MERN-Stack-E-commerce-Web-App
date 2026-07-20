# E-commerce-Web-App-using-MERN-Stack
# 🛒 MERN Stack E-Commerce Web App

A modern Full Stack E-Commerce application built with **React.js**, **Node.js**, **Express.js**, and **MongoDB**. The application provides secure authentication, product browsing, wishlist management, and responsive user interfaces while following a scalable component-based architecture.

---

## 📸 Screenshots

> Add screenshots of the following pages here.

  Login
  <img width="1907" height="956" alt="image" src="https://github.com/user-attachments/assets/b6fc9a6a-da86-4490-a6f4-de8dabda26ff" />

 Register
 <img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/80d37761-9520-4837-a870-dffed5c2cb64" />

 Home
  <img width="1905" height="958" alt="image" src="https://github.com/user-attachments/assets/109da619-cb2a-44e6-8d06-02ef91d52070" />

  All Products
  <img width="1919" height="904" alt="image" src="https://github.com/user-attachments/assets/19b0bac5-f013-4573-8889-4e933e396d7a" />

  Product Details
  <img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/c9a86f4c-7358-4ffd-bf96-a4cf5eb1a7f2" />

  Wishlist
  <img width="1920" height="956" alt="image" src="https://github.com/user-attachments/assets/b2fb06ed-4595-4664-b010-142a54ca9b32" />

 Profile
  <img width="1905" height="958" alt="image" src="https://github.com/user-attachments/assets/da275767-52ed-40a1-b198-b2c5941874d2" />


 

 

# 🚀 Features

## Authentication

- User Registration
- User Login
- JWT Authentication
- Protected Routes
- Session-based Authentication
- Dynamic Navbar based on Authentication State

---

## User

- View Profile
- Update User Information
- Secure Authentication Flow

---

## Products

- Browse Products
- View Product Details
- Responsive Product Cards

---

## Wishlist

- Add Products to Wishlist
- Remove Products from Wishlist
- View Saved Products

---

## UI

- Responsive Design
- Bootstrap 5
- React Router Navigation
- Error Pages (404)
- Loading States

---

# 🏗️ System Architecture

```
                 React UI
                     │
             React Router DOM
                     │
            Context API (Auth)
                     │
              Fetch API Requests
                     │
        Node.js + Express REST API
                     │
                MongoDB Database
```

---

# 🔄 Application Flow

```
User Action
      │
      ▼
React Component
      │
      ▼
Context API
      │
      ▼
Fetch API
      │
      ▼
Express API
      │
      ▼
MongoDB
      │
      ▼
Response
      │
      ▼
UI Update
```

---

# 🔐 Authentication Flow

```
User Login
      │
      ▼
POST /login
      │
      ▼
Backend Validation
      │
      ▼
JWT Generated
      │
      ▼
sessionStorage
      │
      ▼
AuthContext Updated
      │
      ▼
Protected Routes Accessible
```

---

# 🧰 Tech Stack

## Frontend

- React 19
- Vite
- React Router DOM v7
- Context API
- Bootstrap 5
- Bootstrap Icons
- Font Awesome
- Fetch API

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt
- Multer

---

# 📂 Project Structure

```
src/
│
├── assets/
├── components/
├── context/
├── hooks/
├── pages/
├── services/
├── utils/
│
├── App.jsx
└── main.jsx
```

---

# 📄 Available Pages

| Route | Description |
|--------|-------------|
| / | Login / Register |
| /home | Homepage |
| /allproducts | Products |
| /singleproduct/:id | Product Details |
| /wishlist | Wishlist |
| /account | User Profile |
| * | 404 Not Found |

---

# 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /login | Login User |
| POST | /register | Register User |
| GET | /products | Get Products |
| GET | /products/:id | Product Details |
| GET | /wishlist | Get Wishlist |
| POST | /wishlist | Add to Wishlist |
| DELETE | /wishlist/:id | Remove from Wishlist |

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/project-name.git
```

Move to project

```bash
cd project-name
```

Install dependencies

```bash
npm install
```

Run development server

```bash
npm run dev
```

---

# 🔧 Environment Variables

Create a `.env` file

```env
VITE_API_URL=http://localhost:5000/api
```

---

# 🔑 Key Concepts

- Component-based Architecture
- Context API
- Authentication
- Protected Routes
- REST API Integration
- Global State Management
- Responsive UI
- Reusable Components

---

# 🛡️ Security

- JWT Authentication
- Password Hashing (bcrypt)
- Protected Routes
- Authentication Middleware
- Input Validation

---

# 🤖 AI-Assisted Development

AI tools were used to improve productivity during development by assisting with:

- Component scaffolding
- Debugging and error analysis
- Code refactoring suggestions
- API design discussions
- Documentation improvements

All generated suggestions were reviewed, tested, and integrated manually.

---

# ⚠️ Current Limitations

- No Shopping Cart
- No Checkout System
- No Product Search
- No Filtering
- Limited Product Categories

---

# 🚀 Future Improvements

- Shopping Cart
- Checkout & Payment
- Product Search
- Product Filtering
- Admin Dashboard
- Order Management
- Product Reviews
- Performance Optimization
- Unit Testing
- TypeScript Migration

---

# 📚 What I Learned

- Building scalable React applications
- JWT Authentication
- REST API Integration
- Authentication Flow
- Context API State Management
- Component Reusability
- API Error Handling
- Responsive UI Development

---

# 💡 Challenges

Some challenges faced during development included:

- Managing authentication state across the application
- Keeping the UI synchronized after login/logout
- Integrating frontend with backend APIs
- Protecting private routes
- Handling API errors gracefully

---

# 👨‍💻 Author

**Amr Mohamed Bayoumi**

- GitHub: https://github.com/AmrMhmdBayoumi93
- LinkedIn: *( https://www.linkedin.com/in/amr-muhammad-bayoumi-193b1535a/)*

---

## ⭐ If you like this project, don't forget to give it a Star.

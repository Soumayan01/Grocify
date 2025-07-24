# 🛒 Grocify – MERN Stack Grocery E-Commerce Website

**Grocify** is a full-stack, responsive grocery e-commerce platform built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). It supports both customer and seller functionalities including secure login, product browsing, cart management, and order handling. It features two separate panels: one for **customers** and one for **sellers/admins**.

---

## 🚀 Features

### 👥 Customer Panel:
- Account Registration and Login
- Browse grocery products by categories
- Add products to cart
- Place orders via Cash on Delivery (COD) or Online Payment (Stripe/Razorpay)
- View order history and profile

### 🛍️ Seller/Admin Panel:
- Seller authentication and login
- Add new grocery products with image, name, price, stock, and category
- Edit/update product information and stock
- View orders placed by customers
- Manage product availability in real-time

---

## 🧱 Tech Stack

| Layer          | Technology                         |
|----------------|-----------------------------       |
| Frontend       | React.js, HTML5, CSS3              |
| Backend        | Node.js, Express.js                |
| Database       | MongoDB                            |
| Authentication | JWT, bcrypt                        |
| Payment        | Stripe API / Razorpay API          |
| Styling        | Tailwind CSS / Bootstrap (if used) |

---

## 🔐 Authentication & Security

- JWT-based authentication system
- Passwords hashed using bcrypt
- Role-based access for customers and sellers

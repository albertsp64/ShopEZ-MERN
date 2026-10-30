# 🛒 ShopEZ - MERN Stack E-Commerce Platform

ShopEZ is a modern, responsive full-stack e-commerce web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides seamless user authentication, a dynamic product catalog, interactive shopping cart management, order tracking, and an administrative dashboard for inventory and transaction monitoring.

---

## 🚀 Key Features

* **User Authentication & Role-Based Access Control (RBAC)**: Secure registration and login workflows with automated role differentiation for customers and administrators.
* **Dynamic Product Catalog**: Real-time product browsing fetched directly from the database.
* **Shopping Cart & Checkout**: Add items, adjust quantities, calculate totals dynamically, and process checkouts.
* **Order History & Tracking**: Customers can view their past orders, while administrators can oversee platform-wide transactions.
* **Admin Dashboard**: Comprehensive control panel for managing products and monitoring store operations.

---

## 🛠️ Tech Stack

* **Frontend**: React.js, React Router, HTML5, CSS3, JavaScript (ES6+), Axios
* **Backend**: Node.js, Express.js, RESTful APIs
* **Database**: MongoDB, Mongoose ODM

---

## 📁 Project Architecture & Structure

The project is structured into a decoupled 3-tier MERN architecture:
* `client/`: React Single Page Application (SPA) frontend interface.
* `server/`: Node.js & Express.js backend containing routes, controllers, and Mongoose database models.

---

## ⚙️ Setup & Installation

1. Clone or extract the project repository.
2. **Backend Setup**:
   * Navigate to the `server` directory.
   * Install dependencies: `npm install`
   * Configure your MongoDB connection string in your environment or configuration files.
   * Start the backend server: `npm start` (Runs on port `3001`).
3. **Frontend Setup**:
   * Navigate to the `client` directory.
   * Install dependencies: `npm install`
   * Start the React client: `npm start`

---

## 📄 Documentation

For full project design details, technical architecture, and API specifications, please refer to the project documentation included in the repository.

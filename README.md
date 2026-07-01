# 🍽️ Cravio - Smart Restaurant & Analytics Management System

Cravio is a unified **Restaurant Management and Business Analytics System** that streamlines restaurant operations while providing intelligent business insights. It combines Customer Ordering, Table Reservation, Restaurant Administration, and Data Analytics into a single platform.

## 🚧 Current Development Status

**✅ Completed:**

* Customer Authentication (Registration & Login)
* Interactive Food Menu
* Search & Filter Functionality
* Shopping Cart & Order Placement
* Table Reservation System
* Ratings & Reviews
* Order History
* Admin Dashboard
* Food Management (Add / Edit / Delete)
* Order & Reservation Management
* Food Image Upload
* Email Notification Integration
* Sales & Revenue Analytics
* Food Popularity Analysis
* Customer Insights Dashboard
* Sales Prediction using Machine Learning

**🛠️ Future Enhancements:**

* Online Payment Gateway
* QR Code Menu Ordering
* Inventory Management
* AI-based Food Recommendations
* Multi-Branch Restaurant Support
* Real-time Order Tracking

---

## 📐 System Architecture

Cravio is divided into three major modules to keep the application scalable and maintainable.

### 1. Customer Portal

*Where customers interact with the restaurant.*

* Register & Login
* Browse Food Menu
* Search & Filter Dishes
* Add Items to Cart
* Place Orders
* Reserve Tables
* Submit Ratings & Reviews
* View Order History
* Receive Email Notifications

### 2. Admin Dashboard

*Where restaurant operations are managed.*

* Dashboard Overview
* Food Management
* Order Management
* Reservation Management
* Food Image Upload
* Customer Review Monitoring

### 3. Analytics Engine

*Where business decisions become data-driven.*

* Sales & Revenue Reports
* Food Popularity Analysis
* Customer Insights Dashboard
* Sales Prediction using Machine Learning
* Interactive Data Visualization

---

## 📊 System Flow

```mermaid
graph TD

login[Register / Login] --> auth[Authentication]
browse[Browse Menu] --> menuAPI[Menu API]
cart[Add to Cart] --> orderAPI[Order Management]
reserve[Reserve Table] --> reservationAPI[Reservation Management]

menuAPI --> database[(Database)]
orderAPI --> database
reservationAPI --> database```

---

## 📈 Analytics Module

Cravio transforms restaurant data into meaningful business insights.

### 📊 Sales & Revenue Analytics

* Monitor daily, weekly, and monthly revenue.
* Track sales performance through interactive charts.
* Identify business growth trends.

### 🍕 Food Popularity Analysis

* Discover best-selling dishes.
* Analyze customer ordering patterns.
* Compare food performance over different periods.

### 👥 Customer Insights

* Understand customer purchasing behavior.
* Monitor order frequency.
* Analyze customer engagement through reviews and ratings.

### 🤖 Sales Prediction

* Predict future sales using historical order data.
* Support inventory planning.
* Help restaurant owners make informed business decisions using machine learning.

---

## 🚀 Features

### 🍽️ Customer Features

* Secure User Registration & Login
* Browse Food Menu
* Search & Filter Food Items
* Shopping Cart
* Online Order Placement
* Table Reservation
* Ratings & Reviews
* Order History
* Email Notifications

### 👨‍💼 Admin Features

* Admin Dashboard
* Food Management
* Order Management
* Reservation Management
* Food Image Upload

### 📊 Analytics Features

* Sales & Revenue Dashboard
* Food Popularity Reports
* Customer Insights Dashboard
* Sales Prediction
* Interactive Data Visualization

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js

### Data Analytics & Machine Learning

* Python
* Pandas
* Plotly
* Scikit-learn

---

## 📂 Repository Structure

```text
/
├── client/             # React Frontend
├── server/             # Node.js + Express Backend
├── analytics/          # Python Analytics & Machine Learning
├── uploads/            # Food Images
├── dataset/            # Sales Dataset
└── README.md
```

---

## 🎯 Project Goals

* Simplify restaurant operations through a centralized management system.
* Provide a seamless ordering and reservation experience for customers.
* Enable restaurant owners to make data-driven business decisions.
* Visualize sales and customer trends through interactive dashboards.
* Predict future sales using machine learning to improve planning and profitability.

---

## 📄 License

This project is intended for educational, research, and learning purposes.

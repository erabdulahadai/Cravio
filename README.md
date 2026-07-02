# Multi-Restaurant Food Ordering & Analytics System

## Project Overview

A full-stack multi-restaurant food ordering platform where customers can browse restaurants, explore menus, place food orders, reserve tables, and submit reviews. Restaurant owners can manage their own restaurants, menus, and orders, while a Super Admin manages the entire platform. The system also includes a Python-based analytics module to generate business insights such as sales reports, restaurant performance, food popularity, and revenue trends.

---

# Objectives

* Develop a multi-vendor restaurant platform.
* Cover maximum topics from FSD-2.
* Cover major topics from FCSP-2.
* Implement role-based authentication.
* Generate business analytics using restaurant data.

---

# Technology Stack

### Frontend

* React.js
* React Router
* Axios
* Bootstrap

### Backend

* Python
* Django
* Django REST Framework (DRF)

### Database

* MongoDB Atlas
* MongoEngine (Django ODM for MongoDB)

### Analytics

* Python
* Pandas
* Plotly
* Seaborn
* Scikit-Learn

---

# System Architecture

```text
                     React Frontend
                            │
                            ▼
                    Django REST API
                            │
             ┌──────────────┴──────────────┐
             ▼                             ▼
        MongoDB Atlas            Python Analytics
             │                   (Pandas/Plotly)
             └──────────────┬──────────────┘
                            ▼
                   Analytics Dashboard
```

---

# User Roles

## Customer

* Register/Login
* Browse Restaurants
* Search Food
* Add to Cart
* Place Orders
* Reserve Tables
* Review Restaurants
* Track Orders

---

## Restaurant Owner

* Register Restaurant
* Manage Restaurant Profile
* Add/Edit/Delete Food Items
* Accept/Reject Orders
* Manage Reservations
* View Restaurant Analytics

---

## Super Admin

* Approve Restaurants
* Manage Users
* Manage Restaurants
* View Overall Analytics
* Monitor Platform Performance

---

# Database Collections

```text
Users
Restaurants
Foods
Categories
Orders
Reservations
Reviews
Cart
```

---

# Main Modules

## Customer Module

* Registration & Login
* Restaurant Listing
* Restaurant Details
* Food Menu
* Cart
* Checkout
* Order History
* Table Reservation
* Ratings & Reviews

---

## Restaurant Owner Module

* Restaurant Dashboard
* Menu Management
* Order Management
* Reservation Management
* Restaurant Profile
* Sales Dashboard

---

## Super Admin Module

* Manage Restaurants
* Manage Customers
* Manage Restaurant Owners
* Platform Statistics
* Revenue Dashboard

---

# Analytics Module

## Restaurant Analytics

* Restaurant-wise Revenue
* Monthly Revenue
* Daily Orders
* Peak Ordering Hours

---

## Food Analytics

* Most Ordered Food
* Least Ordered Food
* Category-wise Sales

---

## Customer Analytics

* Active Customers
* Average Ratings
* Customer Ordering Trends

---

## Platform Analytics

* Top Performing Restaurants
* Revenue Comparison
* Order Growth
* Restaurant Performance Ranking

---

## Prediction Module

Predict:

* Next Month Sales
* Expected Restaurant Revenue

Using:

* Linear Regression

---

# MongoDB Collections

* Users
* Restaurants
* Foods
* Categories
* Cart
* Orders
* Reservations
* Reviews

---

# React Pages

### Public

* Home
* Restaurants
* Restaurant Details
* About
* Contact

### Authentication

* Login
* Register

### Customer

* Cart
* Checkout
* Reservations
* Order History
* Profile

### Restaurant Owner

* Dashboard
* Manage Menu
* Manage Orders
* Manage Reservations
* Analytics

### Super Admin

* Dashboard
* Manage Restaurants
* Manage Users
* Platform Analytics

---

# FSD Topics Covered

* React Components
* BrowserRouter
* Props
* useState
* useEffect
* useContext
* Forms & Validation
* Axios
* REST APIs
* Django URL Routing
* Django Middleware
* Django Sessions & Cookies
* Django File Uploads (Restaurant/Food Images)
* Django Email Backend (SMTP)
* MongoDB
* MongoEngine
* CRUD Operations (Django Views/ViewSets)
* Aggregation (MongoEngine/Pandas)
* Search using Regex
* Authentication & Authorization (Role-Based, Django + DRF)

Coverage: **95%+**

---

# FCSP Topics Covered

* Pandas
* Data Cleaning
* Exploratory Data Analysis (EDA)
* GroupBy & Aggregation
* Plotly Visualizations
* Seaborn Charts
* Revenue Analysis
* Restaurant Performance Analysis
* Customer Analysis
* Linear Regression
* Model Evaluation

Coverage: **75–80%**

---

# Future Enhancements

* Online Payments
* Live Order Tracking
* Google Maps Integration
* Coupons & Offers
* Favorite Restaurants
* Push Notifications
* AI Food Recommendation
* Mobile Application

---

# Expected Outcome

A scalable multi-restaurant food ordering platform that enables customers, restaurant owners, and administrators to interact through a single system while providing analytical insights to improve restaurant performance and business decision-making.

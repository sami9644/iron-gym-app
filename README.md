# 🏋️ Iron Gym — Gym Management & Training Platform

**Iron Gym** is a full-stack gym management and training platform built with **Flask** and **Bootstrap**. It provides gym members with a complete subscription experience while giving trainers and administrators dedicated tools to manage training content, memberships, and trainer applications.

🌐 **Live Demo:** https://iron-gym-j6wf.onrender.com

---

## ✨ Features

### 👤 User Authentication

* User registration and account creation
* Secure user sign-in and sign-out
* Personalized user dashboard
* Subscription status tracking

### 💳 Gym Subscription & Payments

* Online gym subscription system
* **Chapa API** integration for secure payments
* Subscription renewal functionality
* Automatic subscription status tracking
* Expired membership detection
* Alerts for users whose subscriptions have expired

### 🏋️ Trainer System

* Users can apply to become trainers
* Trainer applications are reviewed by administrators
* Admins can **approve or reject** trainer applications
* Approved trainers receive access to their trainer dashboard
* Trainers can upload and publish training content
* Trainers can provide both:

  * 🎥 Normal/on-demand training videos
  * 🔴 Live training sessions

### 🛠️ Admin Dashboard

Administrators can manage the gym platform from a centralized dashboard.

Admin functionality includes:

* Manage registered gym members
* View and manage user subscriptions
* Monitor expired memberships
* Send alerts to users with expired subscriptions
* Review trainer applications
* Approve or reject trainer applications
* Manage trainers and gym users
* Monitor the overall gym platform

### 🔔 Subscription Alerts

The platform helps keep gym membership records up to date by identifying expired subscriptions and notifying affected users so they can renew their memberships.

---

## 🧑‍💻 User Roles

| Role              | Capabilities                                                                                       |
| ----------------- | -------------------------------------------------------------------------------------------------- |
| **Gym Member**    | Register, sign in, subscribe, renew membership, access training content, apply to become a trainer |
| **Trainer**       | Manage training content, publish normal videos, provide live training sessions                     |
| **Administrator** | Manage users, subscriptions, trainer applications, trainers, and membership alerts                 |

---

## 💰 Payment Integration

Iron Gym integrates with the **Chapa Payment API** to handle gym membership payments.

The subscription flow allows users to:

1. Select a gym subscription.
2. Initiate payment through Chapa.
3. Complete the payment.
4. Have their membership status updated.
5. Renew their subscription when it expires.

---

## 🏗️ Technology Stack

### Backend

* **Python**
* **Flask**

### Frontend

* **HTML5**
* **CSS3**
* **Bootstrap**
* **JavaScript**

### Payment

* **Chapa API**

### Deployment

* **Render**

---



> The exact structure may vary depending on the current implementation.

---

## 🔄 Platform Workflow

```text
                    ┌─────────────────┐
                    │     Visitor     │
                    └────────┬────────┘
                             │
                    Register / Sign In
                             │
                             ▼
                    ┌─────────────────┐
                    │   Gym Member    │
                    └────────┬────────┘
                             │
                    Subscribe / Renew
                             │
                             ▼
                    ┌─────────────────┐
                    │ Chapa Payment   │
                    └────────┬────────┘
                             │
                       Payment Success
                             │
                             ▼
                    ┌─────────────────┐
                    │ Active Member   │
                    └────────┬────────┘
                             │
                 ┌───────────┴───────────┐
                 ▼                       ▼
          Training Content        Apply as Trainer
                                         │
                                         ▼
                                ┌─────────────────┐
                                │     Admin       │
                                └────────┬────────┘
                                         │
                                  Approve / Reject
                                         │
                                         ▼
                                ┌─────────────────┐
                                │     Trainer     │
                                └────────┬────────┘
                                         │
                              Upload / Manage Videos
```

---


## 🌐 Live Application

Try the deployed application:

**https://iron-gym-j6wf.onrender.com**

---

## 🔐 Security

The application is designed with common web application security practices in mind, including:

* Authentication and authorization
* Protected admin functionality
* Role-based access control
* Environment variables for sensitive credentials
* Secure payment processing through Chapa
* Server-side validation

---

## 📱 Responsive Design

The frontend is built using **Bootstrap**, allowing the platform to provide a responsive experience across:

* 💻 Desktop
* 📱 Mobile
* 📟 Tablet

---

## 🎯 Project Goals

Iron Gym was developed to provide gyms with a centralized digital platform for managing:

* Gym memberships
* Online payments
* Subscription renewals
* Trainers
* Training videos
* Live training
* Member accounts
* Expired memberships

The goal is to reduce manual membership management while giving gym members convenient access to gym services and training resources online.

---

## 🔮 Future Improvements

Potential future improvements include:

* 📊 Advanced admin analytics and statistics
* 📅 Trainer booking and scheduling
* 💬 Member-to-trainer messaging
* 📱 Dedicated mobile application
* 🔔 Push notifications
* 📧 Email notifications
* 🧾 Digital payment receipts
* 📈 Subscription and revenue reports
* ⭐ Trainer ratings and reviews
* 🗓️ Advanced live-class scheduling

---

## 👨‍💻 Developer

Developed as a full-stack gym management solution using **Python, Flask, Bootstrap, JavaScript, and Chapa API**.

---

## 📄 License

This project is intended for demonstration and portfolio purposes. Add your preferred license here if you plan to distribute the source code publicly.

---

⭐ **If you find this project interesting, consider giving the repository a star!**

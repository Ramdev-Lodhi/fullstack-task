# 🏗️ Realt Trust – Full Stack Development Task

### 👨‍💻 By: Ramdev Lodhi  
**Frontend:** Vercel | **Backend:** Render

---

## 📌 Overview

**Realt Trust** is a full-stack web application developed as part of a full stack development assignment. It features a modern landing page with project and client showcase, a functional contact form, and newsletter subscription — all backed by a powerful admin panel for managing content.

---

## 🌐 Deployment Links

- **Frontend (Vercel):** [View Live Site](https://fullstack-task-sable.vercel.app/)
- **Backend (Render):** [API Server](https://fullstack-task-b58g.onrender.com)

---

## 🎯 Features

### 🚀 Landing Page

- **Our Projects Section:**
  - List of projects fetched from the backend.
  - Each project includes:
    - ✅ Project Image
    - ✅ Project Name
    - ✅ Project Description
    - 🕹️ Read More (dummy)

- **Happy Clients Section:**
  - Showcases all happy clients with:
    - ✅ Client Image
    - ✅ Client Name
    - ✅ Designation
    - ✅ Testimonial/Description

- **Contact Form:**
  - Inputs:
    - Full Name
    - Email
    - Mobile Number
    - City
  - Data stored via backend API.
  - Visible in the admin panel.

- **Newsletter Subscription:**
  - Email field
  - Saves email to backend for future marketing/newsletters.

---

### 🔐 Admin Panel

- **Project Management:**
  - Add new projects with image, name, and description.
  - Image cropping before upload.

- **Client Management:**
  - Add client testimonials with:
    - Client Image
    - Name
    - Designation
    - Description

- **Contact Form Responses:**
  - View all contact submissions from users.

- **Newsletter Emails:**
  - View all subscribed email addresses.

---

## ⚙️ Tech Stack

| Layer      | Technology        |
|------------|-------------------|
| Frontend   | React.js, HTML, CSS |
| Backend    | Node.js, Express.js |
| Database   | MongoDB Atlas (Free Tier) |
| Image Crop | react-easy-crop or similar |
| Deployment | Vercel (Frontend), Render (Backend) |

---

## 🧑‍💻 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/fullstack-task.git
cd fullstack-task

# FruitAi application

## 🛠 Login Credentials (for demo)
**Userid:** `admin`  
**Password:** `password@123`

---

## 📖 Project Overview

This project is a **full-stack web application** developed using **React** for the frontend and **Flask** for the backend. The application has several key features, including a login page, a chatbot page displaying fruit details, a language translator, an FAQ section with CRUD functionality, and an about page. The application is responsive and mobile-friendly.

### 🚀 Live Demo

- **Frontend (Deployed on Netlify):** https://frruuitaii.netlify.app/
- **Backend (Deployed on Render):** https://fruit-ai-15zg.onrender.com/

---

## 🧭 Table of Contents

1. [Login Credentials](#login-credentials-for-demo)
2. [Project Overview](#project-overview)
3. [Live Demo](#live-demo)
4. [Frontend Features](#frontend-features)
5. [Backend Features](#backend-features)


---

## 🌟 Frontend Features

1. **Login Page**:
   - A simple UI for login with a dummy user ID (`admin`) and password (`password123`).
   - On successful login, redirects to the homepage.
   
2. **Home Page**:
   - Displays four services with clickable cards:
     - **Chatbot**: Lists different fruits with details.
     - **Translator**: Allows translation of text to regional languages.
     - **FAQ**: Basic CRUD functionality for FAQs related to fruits.
     - **About Page**: Information about the application.

3. **Chatbot Page**:
   - Displays a list of fruits in card format.
   - Clicking on each fruit shows detailed information.

4. **Translator Page**:
   - Simple input box to translate text into different regional languages.

5. **FAQ Page**:
   - Full CRUD functionality (Create, Read, Update, Delete) for managing FAQs related to fruits.

6. **About Page**:
   - Static content page that provides information about the application and its purpose.

### 📱 Mobile Friendly Design
- The UI/UX is designed to be responsive across all devices, ensuring a seamless user experience on mobile phones and desktops alike.

---

## 🔥 Backend Features

- **Framework**: Flask
- Provides a Fast API to manage FAQs with basic CRUD operations.
  
### CRUD Functionality:
- **GET /faqs**: Fetch all FAQs.
- **GET /faqs/:id**: Fetch a specific FAQ by ID.
- **POST /faqs**: Create a new FAQ.
- **PUT /faqs/:id**: Update a specific FAQ.
- **DELETE /faqs/:id**: Delete a specific FAQ.

---

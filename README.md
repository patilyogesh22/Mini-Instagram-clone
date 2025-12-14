## Task 01

#  📸 Instagram Mini Clone

## Project Overview

This project is a Mini Instagram-style web application developed as part of an assignment task.
It implements the core backend and frontend features of Instagram, including authentication, user relationships, post creation, likes, comments, and a personalized feed.


## ✅ Features Implemented

### Authentication

* User signup and login
* Secure password hashing using bcrypt
* JWT-based authentication
* Protected routes for authenticated users

---

### Follow System

* Follow other users
* Unfollow users
* Maintain followers and following relationships

---

### Post Management

* Create posts with:
  * Image upload using Cloudinary
  * Caption support
* View posts created by followed users
* Delete own posts

---

### Likes

* Like posts
* Unlike posts
* Dynamic like count updates without page refresh

---

### Comments

* Users can comment on posts
* Each comment displays:
* Comment text
* User who commented

---

### Personalized Feed

* Personalized feed API
* Shows posts created by users the logged-in user follows
* Feed updates dynamically without page refresh
---

### Profile Management

* View user profile
* Update profile information
* Upload profile image
* View followers and following count

---

## 🎨 Frontend Screens

* 🔐 Login & Signup

* 🏠 Home Feed

* ➕ Create Post

* 👤 Profile Page

* 📄 Post Detail Page

## 🛠️ Tech Stack

### Backend Technology

* Node.js
* Express.js
* MongoDB
* JWT (JSON Web Tokens)
* bcryptjs
* Cloudinary
* cors
---

### Frontend Technology

* React.js
* React Router DOM
* Redux Toolkit
* Axios
* Tailwind CSS
* react-icons
---

## 📂 Project Structure

```
Mini-Instagram-clone/
    │
    ├── backend/
    │   ├── controllers/
    │   ├── models/
    │   ├── routes/
    │   ├── middleware/
    │   └── server.js
    │
    ├── frontend/
    │   ├── components/
    │   ├── pages/
    │   ├── redux/
    │   └── App.jsx
    │
    └── README.md
```

---
## How to Run the Project

### Backend Setup

```bash
cd backend
npm install
npm start
```

Create a `.env` file inside the backend directory:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
```

---

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

---

## Learning Outcomes

* Implemented secure authentication using JWT
* Understood MongoDB schema relationships
* Built RESTful APIs using Express.js
* Managed frontend state efficiently using Redux Toolkit
* Gained hands-on experience with full-stack application development

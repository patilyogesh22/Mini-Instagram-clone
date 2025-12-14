# 📸 Instagram Mini Clone

This project is a Mini Instagram-style web application developed as part of an assignment task.
It implements the core backend and frontend features of Instagram, including authentication, user relationships, post creation, likes, comments, and a personalized feed.

# 🎯 Task Objective

    To build a basic Instagram-like application that demonstrates:
    Secure user authentication
    Follow / unfollow relationships
    Content creation (posts)
    Engagement features (likes & comments)
    Personalized feed generation

# ✅ Features Implemented (As Per Task PDF)

1️⃣ User Authentication

        User signup and login
        Password hashing using bcrypt
        JWT-based authentication for protected routes

2️⃣ Follow System

        Users can follow other users
        Users can unfollow users
        Proper follower–following relationships maintained in the database

3️⃣ Post Creation

        Only authenticated users can create posts
        Each post contains:
        Image URL
        Caption

4️⃣ Likes

        Users can like posts
        Users can unlike posts
        Like count updates dynamically

5️⃣ Comments

        Users can comment on posts
        Each comment displays:
        Comment text
        User who commented

6️⃣ Feed

        Personalized feed API
        Shows posts created by users the logged-in user follows
        Feed updates dynamically without page refresh


# 🎨 Frontend Screens
🔐 Login & Signup
🏠 Home Feed
➕ Create Post
👤 Profile Page
📄 Post Detail Page


# 🛠️ Technology Stack
# Backend Technology

    Node.js
    Express.js
    MongoDB
    JWT (Authentication)
    bcryptjs
    Cloudinary (image storage)

# Frontend Technology

    React.js
    React Router DOM
    Redux Toolkit
    Tailwind CSS
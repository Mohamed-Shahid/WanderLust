# WanderLust 🌍

Hey there! 👋  
Welcome to **WanderLust** — a simple, full-stack web app inspired by Airbnb. Here, users can list, view, edit, and delete properties (like campgrounds or stays). It’s built with **Node.js, Express, MongoDB**, and uses **EJS** for rendering pages.

This project helped me learn the complete backend flow — authentication, authorization, CRUD operations, and handling file uploads.

---

## 🚀 What You Can Do Here

- Create your own account (signup/login)
- Add new property listings with images
- Edit or delete only your own listings (authorization in place!)
- View all listings created by others
- Get success and error flash messages while performing actions

---

## 🔧 Tech Used

- **Backend:** Node.js, Express.js
- **Frontend:** EJS Templating
- **Database:** MongoDB with Mongoose
- **Authentication:** Passport.js (Local Strategy)
- **File Uploads:** Multer + (optionally) Cloudinary
- **Other stuff:** Method-Override, Express-Session, Connect-Flash, Helmet

---

## 🛠️ How to Run It Locally?

1. **Clone the repo:**

2. **Install all dependencies:**

   -npm install

3.**Setup your .env file like this:**

  -DB_URL=your_mongodb_url
  -CLOUDINARY_CLOUD_NAME=your_cloudinary_name
  -CLOUDINARY_API_KEY=your_api_key
  -CLOUDINARY_API_SECRET=your_api_secret
  -SECRET=any_random_secret_key

4. **Start the app:**

  -npm start

5. **Open http://localhost:3000 in your browser.**

# 🌍 Wanderlust – Full Stack Travel Listing Web App

🚀 **Live Demo:**
👉 [https://wanderlust-project-0d3i.onrender.com/listings](https://wanderlust-project-0d3i.onrender.com/listings)

---

## 📌 Project Overview

**Wanderlust** is a full-stack web application that allows users to explore, create, and review travel destinations.
The platform includes **secure authentication**, **image uploads**, **map-based location visualization**, and **persistent session management**, deployed on **Render** with **MongoDB Atlas**.

This project demonstrates strong hands-on experience with **backend development, authentication, cloud services, and deployment**.

---

## ✨ Key Features

* 🔐 **User Authentication & Authorization**

  * Register & Login using Passport.js
  * Secure password hashing
  * Authorization rules (only owners can edit/delete listings)

* 🏕️ **Listings Management**

  * Create, edit, and delete travel listings
  * Upload image for the listing
  * Only authenticated users can manage listings

* ⭐ **Reviews & Ratings**

  * Add and delete reviews
  * Authorization enforced for review ownership

* 🗺️ **Map Integration**

  * Interactive maps using Mapbox
  * Location-based visualization for listings

* ☁️ **Cloud & Database**

  * Images stored on Cloudinary
  * MongoDB Atlas for scalable data storage
  * Sessions stored in MongoDB using connect-mongo

* 💬 **User Experience**

  * Flash messages for feedback
  * Responsive UI
  * Error handling with custom error pages

---

## 🛠️ Tech Stack

### Frontend

* EJS
* HTML5
* CSS3
* Bootstrap

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* Passport.js
* Express-Session
* connect-mongo

### Cloud & APIs

* Cloudinary (Image Storage)
* Mapbox (Maps & Geocoding)

### Deployment

* Render (Backend Hosting)
* MongoDB Atlas (Database)

---

## 📂 Project Structure

```
Wanderlust-Project/
├── controllers/        ← Custom route logic (user/listing handlers)
├── init/               ← Initialization (likely DB or config setup)
├── models/             ← Mongoose models (User, Listing, Review, etc.)
├── public/             ← Static assets (CSS, JS, images, etc.)
├── routes/             ← Express route definitions
├── utils/              ← Utility helpers (custom errors, middleware)
├── views/              ← EJS templates
├── .gitignore          ← Files/folders ignored by Git
├── app.js              ← Main Express server file
├── cloudconfig.js      ← Cloudinary config
├── middleware.js       ← Custom middleware functions
├── package.json        ← Project dependencies & scripts
├── package-lock.json   ← Locked dependency versions
└── schema.js           ← Joi or validation schema definition
``` :contentReference[oaicite:1]{index=1}

### 📌 Summary
- **controllers/** – Handles logic for routes (e.g., create, update)
- **models/** – Database schemas
- **routes/** – API/URL routing
- **views/** – UI templates (EJS)
- **utils/** – Helpers & error utilities
- **public/** – Static front-end files
- **app.js** – Entry point for the application
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory and add:

```env
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MAP_TOKEN=your_mapbox_token
ATLASDB_URL=your_mongodb_atlas_connection_url
SECRET=your_session_secret
```

---

## ▶️ Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/wanderlust.git

# Move into the project directory
cd wanderlust

# Install dependencies
npm install

# Start the server
node app.js
```

Visit:

```
http://localhost:3000
```

---

## 🌐 Deployment

* Deployed on **Render**
* MongoDB hosted on **MongoDB Atlas**
* Environment variables securely configured on Render dashboard

🔗 **Live URL:**
[https://wanderlust-project-0d3i.onrender.com/listings](https://wanderlust-project-0d3i.onrender.com/listings)

---

## 🎯 Learning Outcomes

* Implemented **secure authentication & authorization**
* Worked with **cloud storage and third-party APIs**
* Built **RESTful routes** with Express
* Managed **sessions at scale** using MongoDB
* Gained hands-on experience with **production deployment**

---

## 👨‍💻 Author

**Sanjeev Gosai**
Interested in Full Stack Development & Scalable Web Applications

---

## ⭐ If you like this project

Give it a ⭐ on GitHub — it helps a lot!

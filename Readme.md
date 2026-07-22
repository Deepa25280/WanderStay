# 🏡 WanderStay

WanderStay is a full-stack accommodation listing web application inspired by modern vacation rental platforms. It allows users to explore travel destinations, view property listings, create and manage their own listings, and share reviews.

The project is built using the **MERN-style JavaScript ecosystem with Node.js, Express.js, MongoDB, and EJS** for server-side rendering.

🔗 **Live Demo:** https://wanderstay-h2wb.onrender.com/listings
---

## ✨ Features

* 🔐 **User Authentication**

  * User registration and login
  * Secure session-based authentication
  * Login/logout functionality
  * Authorization for protected routes

* 🏡 **Property Listings**

  * View all available stays
  * View detailed information about individual properties
  * Create new property listings
  * Edit existing listings
  * Delete listings
  * Add property images

* ⭐ **Reviews & Ratings**

  * Add reviews to listings
  * Give ratings to properties
  * Delete reviews
  * Display reviews on listing pages

* 🗺️ **Location-Based Features**

  * Property location information

* ⚠️ **Error Handling**

  * Custom error handling
  * Express error middleware
  * Async error handling using `wrapAsync`

---

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript
* EJS
* Bootstrap

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication & Security

* Passport.js
* Express Session
* Connect-Mongo

### Other Tools

* Method Override
* EJS-Mate
* Dotenv
* Cloudinary 
---

## 📂 Project Structure

```text
WanderStay/
├── controllers/
├── init/
├── models/
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── public/
│   ├── css/
│   │   ├── rating.css
│   │   └── style.css
│   └── js/
│       └── script.js
├── routes/
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── utils/
│   ├── ExpressError.js
│   └── wrapAsync.js
├── views/
│   ├── includes/
│   ├── layouts/
│   ├── users/
│   │   ├── login.ejs
│   │   └── signup.ejs
│   ├── listings/
│   └── error.ejs
├── app.js
├── middleware.js
├── package.json
├── package-lock.json
└── .env
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Deepa25280/WanderStay.git
```

Navigate to the project directory:

```bash
cd WanderStay
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_key
CLOUD_API_SECRET=your_cloudinary_secret
```

### 4. Start the Application

For development:

```bash
node app.js
```

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:8080
```

---

## 🌐 Live Deployment

WanderStay is deployed and hosted on **Render**.

🔗 **Live Demo:** https://wanderstay-h2wb.onrender.com/listings

The application is connected to MongoDB Atlas for database management and is configured with the required environment variables on Render.

### Deployment Stack

* **Hosting:** Render
* **Database:** MongoDB Atlas
* **Source Code:** GitHub
* **Backend:** Node.js + Express.js
---

## 🔒 Environment Variables

`.env` is included in `.gitignore`:

```gitignore
.env
node_modules/
```
---

## 🗺️ Future Improvements

* [ ] Add interactive maps using Leaflet and OpenStreetMap
* [ ] Add search and filtering functionality
* [ ] Add categories for different types of stays
* [ ] Add wishlist/favorites
* [ ] Add booking functionality
* [ ] Add payment integration
* [ ] Improve mobile responsiveness
* [ ] Add advanced location-based search

---

## 👩‍💻 Author

**Deepa Yadav**

B.Tech CSE-DS 

---

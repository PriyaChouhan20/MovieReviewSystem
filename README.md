

 🎬 Movie Review System

A scalable RESTful backend application for managing movies and user reviews, built using Node.js, Express.js, and MongoDB following MVC architecture.

 📌 Project Overview

The Movie Review System is a backend web application that allows users to:

* Manage movie records
* Add and delete reviews
* Perform CRUD operations
* Structure backend using MVC pattern
* Build scalable REST APIs

This project demonstrates strong understanding of backend development concepts, routing, middleware, database integration, and API design.


 🚀 Features

* Create, Read, Update, Delete Movies
* Add & Delete Reviews
* RESTful API design
* MVC Architecture
* Environment variable configuration
* Clean folder structure

 🛠️ Tech Stack

* **Node.js**
* **Express.js**
* **MongoDB**
* **Mongoose**
* **JavaScript**
* **REST API**


 📂 Folder Structure

MovieReviewSystem/
│
├── controllers/
├── models/
├── routes/
├── middleware/
├── database/
├── server.js
├── package.json
└── .gitignore

⚙️ Installation Guide

 1️⃣ Clone Repository


git clone https://github.com/PriyaChouhan20/MovieReviewSystem.git


2️⃣ Navigate to Folder

cd MovieReviewSystem 

 3️⃣ Install Dependencies

npm install


 4️⃣ Setup Environment Variables

Create `.env` file:


PORT=5000
MONGO_URI=your_mongodb_connection_string


 5️⃣ Start Server


npm start


Server runs at:


http://localhost:5000




📌 API Endpoints

🎥 Movies

| Method | Endpoint    | Description      |
| ------ | ----------- | ---------------- |
| GET    | /movies     | Get all movies   |
| GET    | /movies/:id | Get single movie |
| POST   | /movies     | Add new movie    |
| PUT    | /movies/:id | Update movie     |
| DELETE | /movies/:id | Delete movie     |

### ⭐ Reviews

| Method | Endpoint          | Description   |
| ------ | ----------------- | ------------- |
| POST   | /reviews/:movieId | Add review    |
| DELETE | /reviews/:id      | Delete review |


 🔮 Future Enhancements

* JWT Authentication
* Rating System
* Search & Pagination
* Role-based Authorization
* Frontend Integration (React)


 👩‍💻 Author

Priya Chouhan
B.Tech Computer Science Student






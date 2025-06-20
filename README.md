

# 🎥 Movie Recommendation App

A full-featured movie recommendation platform where users can discover, search, and save their favorite movies.

## 🚀 Overview

This application connects a **React frontend** to an **Express.js backend**, integrates **JWT authentication**, and uses **MongoDB** as the database. It also communicates with an external movie API (e.g., TMDB) for real-time movie data and recommendations.

---

## 🖥️ Frontend

### Features

* Modern and responsive design for both mobile and desktop.
* User authentication (Login & Signup).
* Search movies by title, genre, or year.
* Filter movies by rating, release date, and popularity.
* Save favorite movies and create watchlists.
* View movie details and personalized recommendations.

### Tech Stack

* **React.js**: Frontend framework.
* **Styled-components**: CSS-in-JS styling.
* **Axios**: For making API requests.
* **React Router**: For navigation.
* **Netlify/Vercel**: For deployment.

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/matthewzegekwe/capstone_project
   cd frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file:

   ```env
   REACT_APP_API_URL=http://localhost:5000
   REACT_APP_TMDB_API_KEY=your_tmdb_api_key
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Deploy using **Netlify** or **Vercel**.

---

## 🔧 Backend

### Features

* RESTful API with Express.js.
* Secure user authentication using JWT.
* Movie data management with MongoDB.
* Integration with TMDB API for movie details.
* User sessions and profile management.

### Tech Stack

* **Express.js**: Backend framework.
* **MongoDB**: Database.
* **Mongoose**: For object data modeling.
* **JWT**: For secure authentication.
* **Render/Heroku**: For deployment.

### API Endpoints

| Method | Endpoint         | Description              |
| ------ | ---------------- | ------------------------ |
| POST   | `/auth/signup`   | Register a new user      |
| POST   | `/auth/login`    | Login a user             |
| GET    | `/movies/search` | Search for movies        |
| POST   | `/favorites/add` | Add a movie to favorites |
| GET    | `/watchlist`     | Retrieve user watchlist  |

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo-url
   cd backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   TMDB_API_KEY=your_tmdb_api_key
   ```

4. Start the server:

   ```bash
   npm start
   ```

5. Deploy using **Render** or **Heroku**.

---

## 🛠️ Hands-On Features

* **Authentication**: Secure user login and registration with hashed passwords.
* **Search & Filter**: Search movies with filtering options.
* **Favorites & Watchlist**: Save and organize favorite movies.

---

## 🌟 Deployment

### Frontend

* **Netlify/Vercel**: Deploy React app with a single command.
* Continuous integration using GitHub Actions.

### Backend

* **Render/Heroku**: Deploy Node.js backend.
* CI/CD pipeline for seamless updates.

---

## 📋 Stretch Goals

* Social features: Follow other users, share movie lists.
* Advanced recommendation algorithm.
* Integration of movie trailers.
* Progressive Web App (PWA) functionality

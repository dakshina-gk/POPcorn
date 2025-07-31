
POPcorn - Movie Explorer App

A fully responsive React web application where users can explore movies, search by title, view trending content, register/login, and save favorites. The backend is built with Node.js, Express, and PostgreSQL (hosted on Neon), supporting user authentication with JWT.

Project Overview

POPcorn is designed to demonstrate full-stack development skills with modern React frontend technologies and a secure backend API. It uses TMDb API for movie data and PostgreSQL for user management and favorites. The app includes user registration, login/logout, and protected routes.

Features

Frontend

Responsive UI built with React
Movie browsing, search by title
Trending movies display
User authentication with JWT (login/register)
Favorite movies saved locally or synced
Dark/light mode toggle (optional to implement)
Profile icon in navbar with dropdown showing user info and logout
Backend

RESTful API using Express.js
PostgreSQL database hosted on Neon
User authentication with hashed passwords (bcrypt) and JWT
Routes for register, login, and protected user info
Error handling for common cases
Tech Stack

Frontend: React, React Router, Axios
Backend: Node.js, Express, PostgreSQL (Neon)
Authentication: JWT, bcrypt
API: TMDb for movie data
State Management: React Context API or useState
Styling: CSS Modules or Tailwind CSS (your choice)
Development: Vite (frontend), nodemon (backend)

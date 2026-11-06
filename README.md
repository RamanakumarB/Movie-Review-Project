# Movie Review Application

A complete, backend based application that allows users to browse a catalog of movies, watch YouTube trailers, and submit reviews.

This project was built following a comprehensive full-stack course, but has been heavily upgraded and adapted to use modern framework versions, including Spring Boot 4.1.x, Java 21, and React 18.

## 🛠️ Tech Stack

**Backend:**
- **Java 21** (Microsoft JDK)
- **Spring Boot 4.1.2** (Spring Web, Spring Data MongoDB)
- **Maven** & **Lombok**

**Frontend:**
- **React 18** (Downgraded from 19 for Material UI Carousel compatibility)
- **React Router** for client-side navigation
- **Axios** for HTTP requests
- **React Bootstrap** & **Material UI**
- **ReactPlayer 3.x** for trailer playback

**Database:**
- **MongoDB Atlas** (Cloud Database)

---

## ✨ Features
- **Movie Catalog:** Browse a carousel of featured movies fetched from the database.
- **Watch Trailers:** Click on a movie to instantly play its YouTube trailer.
- **Read & Write Reviews:** View existing reviews for specific movies and submit your own directly to the database.
- **Separation of Concerns:** Client and Server are completely decoupled, communicating via a RESTful API.

---

## 📂 Project Structure

This repository is a monorepo containing both the backend and frontend code:

```text
Movie-Review-Project/
├── backend/       # Java / Spring Boot REST API
├── frontend/      # React Client
├── .gitignore
└── README.md
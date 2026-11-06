# Full-Stack Movie Review API

A robust Java REST API built with Spring Boot and MongoDB Atlas to serve movie data, trailers, and user reviews. This backend powers a React frontend application.

## Tech Stack
* **Java 21**
* **Spring Boot 4.1.2** (Spring Web, Spring Data MongoDB)
* **MongoDB Atlas**
* **Maven**

## Features
* Retrieve all movies or a single movie by IMDb ID.
* Submit and store movie reviews.
* Cross-Origin Resource Sharing (CORS) enabled for frontend integration.

## Setup Instructions
1. Clone this repository.
2. Create a `.env` file in the root directory (use `.env.example` as a template).
3. Add your MongoDB Atlas connection string credentials to `.env`.
4. Run the application via `MoviesApplication.java` or `mvn spring-boot:run`.
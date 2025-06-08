# Online Learning Platform

## Overview
This project is a modern, full-stack web application developed with the MERN stack (MongoDB, Express.js, React.js, Node.js) and Apollo GraphQL. It aims to provide a seamless online learning experience by combining educational resources with social media-inspired features. Users can interact with posts, explore diverse content, and connect with others in an engaging and user-friendly environment.

## Key Features

- **User Authentication**:
  - Robust registration, login, and logout functionalities.
  - Google OAuth integration for quick and convenient access.
  - Secure authentication mechanisms using JSON Web Tokens (JWT).
- **Profile Management**:
  - Personalized profiles for managing posts and user details.
  - Tools to create, edit, and review posts effortlessly.
- **Advanced Search**:
  - Comprehensive search functionality to locate posts by keywords, categories, or topics.
- **Social Features**:
  - Enhanced interactivity through options to like, comment on, and share posts.

## Technology Stack

### Frontend
- React.js
- Apollo Client for GraphQL
- HTML and CSS

### Backend
- Node.js
- Express.js
- Apollo Server for GraphQL
- MongoDB with Mongoose

### Authentication
- JWT (JSON Web Tokens)


### Requirements

- Node.js installed on your system.
- A MongoDB Atlas account for database hosting.
- A Google Developer Console project for OAuth setup.

### Installation Steps

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project folder:
   ```bash
   cd OLP_MERN
   ```
3. Install the required dependencies for both frontend and backend:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

### Configuring Environment Variables

- In the `server` directory, create a `.env` file and add the following:

  ```makefile
  PORT=4000
  MONGODB_URI=<your-mongodb-uri>
  JWT_SECRET=<your-jwt-secret>
  GOOGLE_CLIENT_ID=<your-google-client-id>
  GOOGLE_CLIENT_SECRET=<your-google-client-secret>
  ```

### Running the Application

1. Start the backend server:
   ```bash
   cd server
   npm run dev
   ```
2. Launch the frontend:
   ```bash
   cd ../client
   npm start
   ```

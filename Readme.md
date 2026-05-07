# Health & Wellness Backend API

This is the backend server for the Health & Wellness Tracker application developed using Node.js, Express.js, and MongoDB.

The backend handles:
- User authentication
- REST API management
- Database operations
- Goal tracking functionality
- Secure communication between frontend and database

---

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js
- dotenv
- CORS

---

## Features

### Authentication
- User Registration
- User Login
- JWT Token Generation
- Password Encryption using bcrypt

### Goal Management APIs
Users can:
- Create wellness goals
- Fetch saved goals
- Update goals
- Delete goals

### Database Integration
- MongoDB Atlas connection
- Mongoose schema models
- Secure environment variables

### API Handling
- RESTful API structure
- JSON-based responses
- Error handling middleware

---

## Installation

## Install Dependencies

```bash
npm install
```

---

## Environment Variables

Create a `.env` file in the root directory and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## Running the Server

### Start Server

```bash
npm start
```

### Run with Nodemon

```bash
nodemon server.js
```

---

## API Endpoints

### Authentication Routes

#### Register User
```http
POST /api/auth/register
```

#### Login User
```http
POST /api/auth/login
```

---

## Testing APIs

- Postman

---

## Security Features

- Password hashing using bcrypt
- JWT-based authentication
- Protected API routes
- Environment variable protection

---

This project is developed for educational and learning purposes.
# JWT Auth API

Simple JWT authentication API with Express.js and MongoDB.

## Setup

1. Install dependencies:

npm install

2. Create .env file:

PORT=3000
MONGODB_URI=mongodb://localhost:27017/jwt-auth
JWT_SECRET=your-secret-key
JWT_EXPIRES_IN=1h

3. Start server:

npm run dev

## API Endpoints

- POST /api/auth/register - Register user
- POST /api/auth/login - Login (sets HTTP-only cookie)
- GET /api/dashboard - Protected route
- POST /api/auth/logout - Logout

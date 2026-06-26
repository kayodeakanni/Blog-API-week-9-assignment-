# Week_9_Blog_API Assignment 

README
Production Blog API
A production-ready Blog API built with Node.js, Express.js, MongoDB, Mongoose, and Joi validation. This project follows clean backend architecture with proper folder structure, validation middleware, slug generation, full CRUD operations, and search functionality for managing blog articles professionally.

Features
Core Backend
Express.js server setup
MongoDB Atlas database connection
Mongoose schema and model design
Production-ready folder structure
Centralized middleware architecture
Validation & Utilities
Joi request validation
Validation middleware
Slug generator utility
Error handling middleware
Full CRUD Operations
Create Article (POST /articles)
Get All Articles (GET /articles)
Get Single Article by Slug (GET /articles/:slug)
Update Article (PATCH /articles/:slug)
Delete Article (DELETE /articles/:slug)

Advanced Features
Search Articles (GET /articles/search?q=)
Slug-based routing for SEO-friendly URLs
Automatic slug regeneration when title is updated
MongoDB text indexing for fast search

Tech Stack
Node.js
Express.js
MongoDB Atlas
Mongoose
Joi
Nodemon
Postman
Git & GitHub

Project Structure
Week_9_Blog_API/
│
├── config/
│   └── db.js
│
├── controllers/
│   └── articleController.js
│
├── middleware/
│   ├── errorHandler.js
│   └── validate.js
│
├── models/
│   └── article.js
│
├── routes/
│   └── articleRoutes.js
│
├── utils/
│   └── slugGenerator.js
│
├── validators/
│   └── articleValidator.js
│
├── .env
├── .gitignore
├── package.json
├── server.js
└── README.md

Installation
Clone Repository
git clone <your-repository-url>
cd Week_9_Blog_API
Install Dependencies
npm install
Create Environment Variables
Create a .env file in the root directory:

PORT=3002
MONGODB_URI=your_mongodb_connection_string
Run Development Server
npm run dev
Expected output:

Server running on port 3002
MongoDB Connected
API Endpoints
Create Article
POST /articles
Get All Articles
GET /articles
Get Single Article
GET /articles/:slug
Update Article
PATCH /articles/:slug
Delete Article
DELETE /articles/:slug
Search Articles
GET /articles/search?q=backend

Sample Request Body
{
  "title": "Nodejs Backend Guide",
  "content": "Nodejs backend development with MongoDB and Express is powerful for building APIs.",
  "excerpt": "Learn backend development fast.",
  "author": "Opeyemi Ishola",
  "category": "Technology",
  "tags": ["nodejs", "backend", "mongodb"],
  "featuredImage": "https://example.com/image.jpg",
  "status": "published",
  "readingTime": "5 min read"
}

Future Improvements
JWT Authentication
User Registration & Login
Admin Role Management
Pagination
Comments System
Likes / Reactions
Image Upload with Cloudinary
Swagger API Documentation
Deployment on Render
Rate Limiting
Helmet Security
Redis Caching

Author
Kayode Akanni 
Backend Developer | Node.js | Express.js | MongoDB

Focused on building scalable backend systems with clean architecture and production-level standards.

License
This project is for learning, portfolio, and backend engineering practice.

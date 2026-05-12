# Week 10: Backend Basics - Node.js & Express

## Author
- **Name:** _Bonface Mwangi_
- **GitHub:** [@SyntaxSage-tech1](https://github.com/SyntaxSage-tech1)
- **Date:** April 2026

## Project Description
CommunityHub API - A RESTful API built with Node.js and Express.<br> This project demonstrates CRUD operations, middleware, error <br>handling, and proper code organization for backend development.

## Technologies Used
- Node.js
- Express.js
- dotenv (environment variables)
- nodemon (development)

## Features
- Full CRUD operations for posts (GET, POST, PUT, DELETE)
- Query filtering (author, search)
- Sorting (newest, popular)
- Pagination support
- Input validation middleware
- Error handling middleware
- Request logging middleware
- Health check endpoint
- Like/unlike posts functionality

## How to Run
1. Clone this repository
2. Run `npm install`
3. Create `.env` file (copy from `.env.example`)
4. Run `npm run dev` (development) or `npm start` (production)
5. Test API with Postman or Thunder Client at `http://localhost:3000`

## API Endpoints
- `GET /api/health` - Health check
- `GET /api/posts` - List all posts (supports query params)
- `GET /api/posts/:id` - Get single post
- `POST /api/posts` - Create post
- `PUT /api/posts/:id` - Update post
- `DELETE /api/posts/:id` - Delete post
- `PATCH /api/posts/:id/like` - Like a post

## Lessons Learned
- How to set up an Express server
- Building RESTful APIs with proper status codes
- Using middleware for logging, validation, and error handling
- Organizing code with MVC pattern (routes, controllers)
- Environment variable management with dotenv

## Challenges Faced
- Understanding middleware execution order
- Implementing proper error handling with async operations
- Structuring the project for scalability
  

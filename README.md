# Recipe Management App

## Description

This is a Recipe CRUD API built with Node.js, Express.js, and MongoDB using Mongoose for object modeling. The API provides functionality to manage recipes, including creating, retrieving, updating, and deleting recipes.

## Technologies Used

- Node.js: JavaScript runtime environment
- Express.js: Web framework for Node.js
- MongoDB: NoSQL database
- Mongoose: MongoDB object modeling library
- Postman: For API documentation and testing

## Setup

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Create a `.env` file with your MongoDB connection string.
4. Run `node index.js` to start the server.
5. Use Postman to test the API endpoints.

## Features

- Create a new recipe
- Retrieve all recipes
- Retrieve a single recipe by ID
- Update a recipe by ID
- Delete a recipe by ID

## API Endpoints

- `POST /api/v1/recipes` - Create a new recipe
- `GET /api/v1/recipes` - Retrieve all recipes
- `GET /api/v1/recipes/:id` - Retrieve a recipe by ID
- `PUT /api/v1/recipes/:id` - Update a recipe by ID
- `DELETE /api/v1/recipes/:id` - Delete a recipe by ID

## POSTMAN Documentation URL

[POSTMAN API Documentation URL: ](https://documenter.getpostman.com/view/39260343/2sAYBPmEos)
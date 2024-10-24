# E-Commerce Back End

This project is the back end for an e-commerce site. It provides a RESTful API built with Express.js and Sequelize to manage products, categories, and tags in a PostgreSQL database. The API supports CRUD operations for all entities and enables efficient data handling for an e-commerce platform.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Routes](#routes)
- [Walkthrough Video](#walkthrough-video)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/e-commerce-backend.git

2. Install dependencies:

npm install

3. Set up your environment variables in a .env file:

DB_NAME=your_database_name
DB_USER=your_postgresql_username
DB_PASSWORD=your_postgresql_password

4. Create the database using the schema.sql file:

psql -U your_postgresql_username -d your_database_name -f db/schema.sql

5. Seed the database:

npm run seed
 
6. Start the server:

npm start

## Models
The project contains four main models:

Category: Defines product categories.
Product: Stores product information including name, price, and stock.
Tag: Contains product tags.
ProductTag: Handles the many-to-many relationship between products and tags.

## Routes
The API includes the following endpoints:

GET /api/categories: Get all categories
POST /api/categories: Create a new category
PUT /api/categories/
: Update an existing category
DELETE /api/categories/
: Delete a category
Similar routes are available for products and tags.

## Walkthrough Video
Link to the walkthrough video

This video demonstrates:

Connecting to the PostgreSQL database.
Creating and seeding the database.
Starting the application and testing API routes in Insomnia Core.


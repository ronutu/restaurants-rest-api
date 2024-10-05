# Restaurants RESTful API

## Overview
The Restaurants RESTful API is designed to manage restaurant-related data efficiently. The data is divided in three tables: **Restaurants**, **Owners** and **Cities**. The API supports all CRUD (Create, Read, Update, Delete) operations.

* Restaurants endpoints: These are private and secured, requiring JWT token authentication and middleware validation to ensure authorized access.
* Owners and Cities endpoints: These are publicly accessible, allowing unrestricted access for basic data operations.

## Technologies
* Node.js, express, jsonwebtoken, cookie-parser
* Docker
* Prisma
* Postman

# Node-sj-Rest-API-wuth-Mongodb

# Node.js REST API with MongoDB and Express

## Description
This project is a robust and scalable RESTful API built using Node.js, Express, and MongoDB. It supports CRUD (Create, Read, Update, Delete) operations, enabling efficient data management and retrieval. The API is designed with best practices in mind, including authentication, data validation, and error handling.

## Features
- **CRUD Operations:** Endpoints for creating, reading, updating, and deleting resources.
- **Authentication:** Secure user authentication and authorization using JWT (JSON Web Token).
- **Data Validation:** Schema-based data validation with Mongoose to ensure data integrity.
- **Error Handling:** Comprehensive error handling for meaningful error messages and API reliability.
- **Middleware:** Utilizes Express middleware for logging, security, and request parsing.
- **Database:** Flexible and scalable NoSQL data storage with MongoDB.
- **Testing:** Unit and integration tests using Mocha and Chai to ensure API functionality and reliability.

## Technologies Used
- **Backend:** Node.js, Express
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT
- **Testing:** Mocha, Chai

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/YadavInTech/Node-js-RESTful-API.git
    cd Node-js-RESTFUL-API
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the root directory and add the following:
    ```env
    PORT=3000
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_secret_key
    ```

4. Start the server:
    ```bash
    npm start
    ```

## API Endpoints

- **User Registration:** `POST /api/register`
- **User Login:** `POST /api/login`
- **Get All Items:** `GET /api/items`
- **Get Item by ID:** `GET /api/items/:id`
- **Create Item:** `POST /api/items`
- **Update Item:** `PUT /api/items/:id`
- **Delete Item:** `DELETE /api/items/:id`

## Testing

To run tests:
```bash
npm test


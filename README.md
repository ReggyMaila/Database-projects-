# Database-projects-

# E-commerce CRUD API
1. Install dependencies: npm install
2. Run server: node server.js
3. Test endpoints via Postman


# E-commerce CRUD API

## Setup Instructions

1. Install dependencies:
   ```bash
   npm install

2 Import database:
mysql -u root -p < ecommerce.sql

3 Update db.js with your MySQL credentials.

4 Run the server:
node server.js

5 API Endpoints:

Users

POST /users → Create user

GET /users → List all users

PUT /users/:id → Update user

DELETE /users/:id → Delete user


Products

POST /products → Create product

GET /products → List all products

PUT /products/:id → Update product

DELETE /products/:id → Delete product

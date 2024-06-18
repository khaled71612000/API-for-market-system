This repository contains a project for creating an API for a market system. The API is designed to handle various market-related operations.

Features
User Authentication: Implements user registration and login functionality.
Product Management: Allows adding, updating, and deleting products.
Order Processing: Manages customer orders, including creation, updating, and deletion.
Database Integration: Uses a database to store user, product, and order information.
RESTful API: Follows REST principles for API endpoints.

Authentication Module:
- Files: auth.js, middleware.js
- Technologies: JWT, bcrypt

Product Management:
- Files: productController.js, productModel.js, productRoutes.js

Order Management:
- Files: orderController.js, orderModel.js, orderRoutes.js

Database Integration:
- Database: MongoDB
- File: db.js

Additional Utilities:
- Global error handling middleware
- Basic logging for requests and errors

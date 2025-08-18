# E-Commerce Clothing Store
A complete e-commerce clothing store project built using the MERN stack (MongoDB, Express.js, React, Node.js). This project includes features such as JWT authentication for secure user management, Multer for handling image uploads, and Stripe for processing payments (using dummy payment data for testing).

## Repository Structure
The repository is organized into the following folders:

- admin: Contains the admin dashboard for managing products, orders, and users.
- shop-frontend: The React-based frontend for the customer-facing e-commerce store.
- shop-backend: The Node.js and Express.js backend handling API routes, database operations, and business logic.

## Features

- User Authentication: Secure login and registration using JWT.
- Product Management: Admins can add, update, and delete products with image uploads via Multer.
- Shopping Cart: Customers can browse products, add items to the cart, and proceed to checkout.
- Payment Integration: Stripe integration for processing payments (dummy data for testing).
- Responsive Design: The frontend is fully responsive for seamless use across devices.

## Tech Stack

- MongoDB: Database for storing user, product, and order data.
- Express.js: Backend framework for building RESTful APIs.
- React: Frontend library for building the user interface.
Face
- Node.js: Runtime environment for the/backend.
- JWT: For secure authentication.
- Multer: For handling file uploads (product images).
- Stripe: For payment processing (dummy implementation).

## Getting Started
**Prerequisites**

- Node.js (v14 or higher)
- MongoDB (local or cloud instance, e.g., MongoDB Atlas)
- Stripe account (for testing payments)
- Git
  
## Installation

**Clone the repository:**
```sh
git clone https://github.com/username/e-commerce.git
cd e-commerce
```


**Install dependencies:**
```sh
For the backend (shop-backend):cd shop-backend
npm install
```

```sh
For the frontend (shop-frontend):cd shop-frontend
npm install
```

```sh
For the admin dashboard (admin):cd admin
npm install
```




**Set up environment variables:**

- Create a .env file in the shop-backend folder with the following:MONGO_URI=your_mongodb_connection_string
```
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
```


**Run the application:**
```sh
Start the backend:cd shop-backend
npm start
```

```sh
Start the frontend:cd shop-frontend
npm start
```

```sh
Start the admin dashboard:cd admin
npm start
```


**Access the application:**

- Frontend: http://localhost:3000
- Admin Dashboard: http://localhost:3001
- Backend API: http://localhost:5000



## Usage
- Customers: Browse products, add to cart, and checkout using Stripe (dummy payments).
- Admins: Log in to the admin dashboard to manage products, view orders, and handle user accounts.
- Developers: Explore the codebase and customize features as needed.

## Reference
- This project was inspired by the tutorial: Build a MERN E-Commerce App.
  
## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature).
3. Commit your changes (git commit -m 'Add your feature').
4. Push to the branch (git push origin feature/your-feature).
5. Open a pull request.

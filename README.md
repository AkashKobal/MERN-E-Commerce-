# MERN E-commerce Website

Welcome to the MERN E-commerce Website! This full-stack web application is built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) to provide a seamless online shopping experience.

## Features
 
- **User Authentication**: Secure user registration and login with JWT. 
- **Product Management**: Admins can add, edit, and delete products.
- **Shopping Cart**: Users can add products to the cart and proceed to checkout.
- **Order Management**: Track orders, order history, and manage order status.
- **Payment Integration**: Integrated with Stripe for secure payments.
- **Responsive Design**: Mobile-friendly and optimized for various devices.
- **Search and Filter**: Search products by name, category, and more.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AkashKobal/MERN-E-Commerce-.git
    ```
2. Navigate to the project directory:
    ```bash
    cd MERN-E-Commerce-
    ```
3. Install dependencies for both client and server:
    ```bash
    cd client && npm install
    cd ../server && npm install
    ```
4. Create a `.env` file in the server directory and add the following environment variables:
    ```
    MONGO_URI=your_mongo_db_connection_string
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```
5. Start the development server:
    ```bash
    cd server && npm run dev
    cd ../client && npm start
    ```

## Usage

1. Register a new user account or login with an existing account.
2. Browse products and add desired items to the shopping cart.
3. Proceed to checkout and complete the payment using Stripe.
4. Admin users can manage products and orders through the admin dashboard.

## Screenshots

![Home Page](screenshots/home.png)
![Product Page](screenshots/product.png)
![Admin Dashboard](screenshots/admin.png)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


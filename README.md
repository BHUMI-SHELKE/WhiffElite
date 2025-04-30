# WhiffElite

## Description
WhiffElite is a hyperlocal clothing delivery platform that connects customers with nearby stores, enabling fast delivery within minutes based on location. It features role-based access for admins, customers, store owners, and delivery partners, with real-time order tracking, secure PayPal payments, and full product and order management—all built on a modern tech stack including React, Node.js, MongoDB, and Socket.IO.

## Installation
```bash
git clone https://github.com/aaditya-sambare/WhiffElite.git
cd WhiffElite
npm install
```

## Usage
1. Create a `.env` file with your database URI, API keys, and other environment-specific settings.
2. Start the development server:
```bash
npm run dev
```
The server will be running at `http://localhost:3000`.

## API Routes

### Admin Routes
- `GET /api/admin/products`: Get all products
- `POST /api/admin/products`: Create new product
- `PUT /api/admin/products/:id`: Update product
- `DELETE /api/admin/products/:id`: Delete product
- `GET /api/admin/orders`: Get all orders
- `GET /api/admin/orders/:id`: Get a specific order by ID
- `PUT /api/admin/orders/:id/status`: Update order status
- `DELETE /api/admin/orders/:id`: Delete order
- `GET /api/admin/users`: Get all users
- `POST /api/admin/users`: Create new user
- `PUT /api/admin/users/:id`: Update user
- `DELETE /api/admin/users/:id`: Delete user

### Store Routes
- `GET /api/products`: Get all available products
- `GET /api/products/:id`: Get product by ID
- `POST /api/cart`: Add product to cart
- `PUT /api/cart/:id`: Update cart
- `DELETE /api/cart/:id`: Remove product from cart
- `POST /api/checkout`: Proceed to checkout
- `PUT /api/checkout/:id/pay`: Update payment status
- `POST /api/checkout/:id/finalize`: Finalize the order

### Order Routes
- `POST /api/orders`: Place a new order
- `GET /api/orders/:id`: Get order details by ID
- `GET /api/orders`: Get all orders for a user

### User Routes
- `POST /api/users/register`: Register a new user
- `POST /api/users/login`: Login an existing user

## Technologies Used
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT for Authentication
- PayPal SDK for payments

## Screenshots
<img width="1440" alt="Screenshot 2025-05-01 at 3 25 18 AM" src="https://github.com/user-attachments/assets/975c5d64-362f-4a34-8ac2-99520a955d76" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 18 49 AM" src="https://github.com/user-attachments/assets/1099d334-2478-4be0-a312-a87dabc7f631" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 19 35 AM" src="https://github.com/user-attachments/assets/441659bc-0430-4069-b05a-6e023670e149" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 19 49 AM" src="https://github.com/user-attachments/assets/9699fc3c-9328-49a5-9afe-b9fc9a08c0a5" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 19 59 AM" src="https://github.com/user-attachments/assets/23cd280c-9bcb-461b-8a2a-326802fed9ef" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 20 08 AM" src="https://github.com/user-attachments/assets/b5827ac7-9806-49a5-b0c4-064b1c372615" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 20 17 AM" src="https://github.com/user-attachments/assets/1e0ab752-e706-46f4-acbb-9d145b363f12" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 20 35 AM" src="https://github.com/user-attachments/assets/b161278a-1793-4cf3-b53b-3725a01f9fad" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 20 45 AM" src="https://github.com/user-attachments/assets/58d3bf93-2725-4415-87f9-fa7d28cd340c" />
<img width="780" alt="Screenshot 2025-05-01 at 3 21 06 AM" src="https://github.com/user-attachments/assets/4147aa06-748e-4bdf-98a4-6fa97dec7a04" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 21 19 AM" src="https://github.com/user-attachments/assets/503014ce-08ae-4c0c-801f-99d3d7b6fc51" />
<img width="1440" alt="Screenshot 2025-05-01 at 3 23 30 AM" src="https://github.com/user-attachments/assets/3ef8c86b-6b19-428f-83de-01dc045922b4" />
<img width="612" alt="Screenshot 2025-05-01 at 3 24 38 AM" src="https://github.com/user-attachments/assets/704e7aa4-abbc-42b5-828c-5157217d6c61" />






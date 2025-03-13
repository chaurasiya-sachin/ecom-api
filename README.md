# eCommerce API

## Base URL
```
https://ecom-api-ivep.onrender.com
```

## Authentication

### Register User
- **Endpoint**: `POST /api/v1/user/register`

### Login User
- **Endpoint**: `POST /api/v1/user/login`

---

## Product API

### Fetch All Products
- **Endpoint**: `GET /api/v1/products`

### Add a New Product (Admin only)
- **Endpoint**: `POST /api/v1/products`

---

## Order API

### Place an Order
- **Endpoint**: `POST /api/v1/orders`

### Get User's Order History
- **Endpoint**: `GET /api/v1/orders`

---

## Cart API

### Add Items to Cart
- **Endpoint**: `POST /api/v1/cart`

### View Items in Cart
- **Endpoint**: `GET /api/v1/cart`

---

## Wishlist API

### Add Items to Wishlist
- **Endpoint**: `POST /api/v1/wishlist`

### View Wishlist
- **Endpoint**: `GET /api/v1/wishlist`

---

## Technologies Used:
- **Node.js**
- **Express.js**
- **MongoDB**

## Installation:
1. Clone the repository.
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file and add your environment variables.
4. Start the server:
   ```
   npm run start
   ```

## License:
This project is licensed under the MIT License.


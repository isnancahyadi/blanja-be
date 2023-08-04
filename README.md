# Blanja Backend

# This Repository is about Blanja Backend build with Express.js, PostgreSQL and Midtrans for the transaction

Blanja is a platform for buying and selling fashion products.

## Introduction

Blanja is an e-commerce platform that allows users to buy and sell products online. This repository contains the backend code that handles various operations, including user authentication, product management, order processing, and more.

# Features

- Login/Register ( Customer / Seller )
- Get User Data
- Edit Customer Data
- Edit Seller Data
- Upload User Photo
- delete User Data
- Get Product
- Insert Product
- Edit Product
- Delete Product
- Get Address User
- Insert Address User
- Edit Address User
- Delete Address User
- Create Order
- Get Order
- Edit Order
- Delete Order
- Create Payment
- Check Status Payment

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
Prerequisites

- Node.js
- Postgresql

# Installing:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/isnancahyadi/blanja-be.git
cd blanja-be
```

2. Install the required dependencies using npm or yarn:

```bash
npm install
# or
yarn install
```

# The API endpoints are:

### User Route

- `GET /users` - Get all users.
- `POST /register/customer` - Register a new customer.
- `POST /register/seller` - Register a new seller.
- `PATCH /edit/customer` - Edit customer data.
- `PATCH /edit/seller` - Edit seller data.
- `DELETE /users` - Delete users.
- `PATCH /users/photo` - Edit user photo.

### Auth Route

- `POST /customer/login` - Login for customers.
- `POST /seller/login` - Login for sellers.

### Product Route

- `GET /product` - Get all products.
- `GET /product/:id` - Get a product by ID.
- `GET /category` - Get all product categories.
- `POST /product` - Insert a new product.
- `GET /seller/product` - Get products by seller (using JWT).
- `PATCH /product` - Edit a product.
- `DELETE /product` - Delete a product.

### Address Route

- `GET /address` - Get addresses using JWT.
- `POST /customer/address` - Insert a new address for a customer.
- `PATCH /address/edit_address` - Edit address.
- `DELETE /address/delete_address` - Delete address.

### Order Route

- `GET /order` - Get all orders.
- `POST /product/createOrder` - Create a new order.
- `PATCH /editorder` - Edit an order.
- `DELETE /order/delete-order` - Delete an order.

### Payment Route

- `POST /create-payment` - Create a new payment.
- `GET /check-status` - Check payment status.

Feel free to explore the API endpoints to understand how to interact with the Blanja backend.

[ Api Deploy ] : https://rich-teal-camel-tutu.cyclic.app

## Endpoint List Postman

[![Run in Postman](https://run.pstmn.io/button.svg)](https://elements.getpostman.com/redirect?entityId=26602283-18309b59-06d3-4af9-a33e-a95d7c6a0f1a&entityType=collection)

## Related Project

- [Blanja ](https://github.com/isnancahyadi/blanja-fe)
- [Blanja Demo](https://blanja-fe-sigma.vercel.app)

## Authors

For more information about this project or have any question or need help for development, feel free to contact me.

Isnan Arif Cahyadi

<div id="badges">
  <a href="https://www.linkedin.com/in/isnanarifcahyadi/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:isnan.arifc@gmail.com">
    <img src="https://img.shields.io/badge/GMail-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</div>

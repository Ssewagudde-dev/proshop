# ProShop eCommerce Platform

## Features
- Full featured shopping cart
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

## Usage
- Create a MongoDB database and obtain your MongoDB URI 
- Create a PayPal account and obtain your Client ID 

## Env Variables
```bash
- Rename the .env.example file to .env and add the following
- NODE_ENV = development
- MONGO_URI = your mongodb uri
- PORT = 5000
- JWT_SECRET = 'abc123'
- PAYPAL_CLIENT_ID = your paypal client id

```
Change the JWT_SECRET to what you want

## Install Dependencies (frontend and backend)
```bash
npm install
cd frontend
npm install
```

## Run 
```bash

# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```
## Build and Deploy
```bash
# Create frontend prod build
cd frontend
npm run build
```


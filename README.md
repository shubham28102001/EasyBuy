# ECommerce Application built with Node.js, Vue.js, MongoDB, and TailwindCSS

## Features

- This e-commerce platform is built using Node.js, Express.js, MongoDB, Vue.js, and TailwindCSS. It features three roles: Admin, Seller, and User.
- Admins have the ability to manage categories (create, view, update, delete), as well as view and remove users, shops, products, and reviews.
- Sellers can manage their own shop (create, view, update, delete) and handle products.
- Users can apply to become sellers, explore shops and products, manage their user profile, and create or delete reviews.

## Screenshots

Home Page

![Home Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/home.png?raw=true)

Shop Page

![Shop Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/shop.png?raw=true)

Category Page

![Category Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/category.png?raw=true)

Product Page

![Product Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/product.png?raw=true)

Login Page

![Login Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/login.png?raw=true)

Register Page

![Register Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/register.png?raw=true)

User Profile Page

![User Profile Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/user_profile.png?raw=true)

Dashboard Page

![Dashboard Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/dashboard.png?raw=true)

### Admin Sections

Home

![Admin Home Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/admin_home.png?raw=true)

User Management

![Admin User Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/admin_user.png?raw=true)

Shop Management

![Admin Shop Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/admin_shop.png?raw=true)

Product Management

![Admin Product Page](https://github.com/ericnanhu/ecommerce-nodejs/blob/main/screenshots/admin_product.png?raw=true)

## Installation Instruction

Clone this project with the following command:

```bash
git clone https://github.com/ericnanhu/ecommerce-nodejs.git
```

Open the project with your code editor, and change into the **backend**:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Run docker compose to start database:

```bash
docker-compose up
```

Start backend:

```bash
npm run watch
```

Change into **frontend** and install dependencies:

```bash
npm install
```

Start frontend:

```bash
npm run dev
```
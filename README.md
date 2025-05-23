Rabbit
Rabbit is a full-stack e-commerce web application built using the MERN stack (MongoDB, Express, React, and Node.js). It allows users to browse products, add them to the cart, and securely checkout. An admin panel is also available for managing products, users, and orders.

live demo
https://rabbit-nfmc.vercel.app/

Features
User authentication and authorization (register/login/logout)

Product listing with filters (category, price, etc.)

Shopping cart and checkout system

PayPal payment integration

Admin dashboard for managing products, users, and orders

Responsive design for all devices

Tech Stack
Frontend: React, Redux Toolkit, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Authentication: JWT (JSON Web Tokens)

Payments: PayPal REST API

Getting Started
Prerequisites
Node.js and npm

MongoDB installed locally or access to a cloud instance (e.g. MongoDB Atlas)

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Shivam0643/Rabbit.git
cd Rabbit
Install frontend and backend dependencies:

bash
Copy
Edit
cd frontend
npm install
cd ../backend
npm install
Set up environment variables. Create .env files in both frontend and backend with the necessary keys like:

For backend .env:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
Run the development servers:

bash
Copy
Edit
# In backend
npm run dev

# In frontend (open new terminal)
cd frontend
npm start

to clone this repo
https://github.com/Shivam0643/Rabbit.git

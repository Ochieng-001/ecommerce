---

# Ecommerce Website

---

Welcome to the **Ecommerce Website** project! This is a full-stack eCommerce platform built for selling phones, phone accessories, laptops, watches, and offering phone repair services. The project includes a responsive frontend, a robust backend, and a cloud-based MongoDB database.

---

## **Features**

### **User Features**
- **User Authentication**: Register, login, and logout functionality.
- **Product Catalog**: Browse products by category (Phones, Laptops, Watches, Accessories).
- **Product Details**: View detailed product information, including images, descriptions, and reviews.
- **Shopping Cart**: Add/remove products, update quantities, and save items for later.
- **Checkout**: Secure checkout process with multiple payment options.
- **Order History**: View past orders and track current orders.
- **Phone Repair Services**: Book repair services and track repair status.
- **Reviews and Ratings**: Leave reviews and ratings for products.

### **Admin Features**
- **Product Management**: Add, edit, and delete products.
- **Order Management**: View and manage orders.
- **Repair Management**: Manage repair requests and track repair status.
- **Analytics**: View sales reports and customer insights.

---

## **Tech Stack**

### **Frontend**
- **Languages**: HTML, CSS, JavaScript
- **Framework**: React.js
- **Styling**: Tailwind CSS
- **State Management**: Redux

### **Backend**
- **Language**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (Cloud)
- **Authentication**: JWT (JSON Web Tokens)

### **Tools**
- **Version Control**: Git, GitHub
- **API Testing**: Postman
- **Payment Gateway**: Stripe
- **Hosting**: Vercel (Frontend), Render (Backend)

---

## **Installation**

### **Prerequisites**
- Node.js (v16 or higher)
- MongoDB Atlas account
- Git

### **Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/Ochieng-001/ecommerce.git
   cd ecommerce

2. **Set up the backend:**
   cd backend
   npm install

3. Set up the frontend
   cd ../frontend
   npm install

4.- Create a .env file in the backend folder and add the following:
  - MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/<dbname>?retryWrites=true&w=majority
  -PORT=5000
  - JWT_SECRET=your_jwt_secret

5. Start the backend server:
    cd ../backend
    node server.js

6. Start up the developer server:
   cd ../frontend
   npm start

7. Open your browser and navigate to http://localhost:3000 to view the website:


```
---

### Project Structure
   
-ecommerce-website/
-├── frontend/              # React.js frontend
-│   ├── public/            # Static assets
-│   ├── src/               # React components and pages
-│   ├── package.json       # Frontend dependencies
-│   └── ...
-├── backend/               # Node.js + Express backend
-│   ├── models/            # MongoDB schemas
-│   ├── routes/            # API routes
-│   ├── server.js          # Backend entry point
-│   ├── package.json       # Backend dependencies
-│   └── ...
-├── .gitignore             # Files to ignore in Git
-├── README.md              # Project documentation
-└── ...

---

# API Documentation

  ## **Endpoints**
  
**Users:**

-POST /api/users/register - Register a new user.
-POST /api/users/login - Log in an existing user.
-GET /api/users/profile - Get user profile (protected route).

**Products:**
-GET /api/products - Get all products.
-GET /api/products/:id - Get a single product by ID.
-POST /api/products - Add a new product (admin only).
-PUT /api/products/:id - Update a product (admin only).
-DELETE /api/products/:id - Delete a product (admin only).

**Orders:**
-POST /api/orders - Create a new order.
-GET /api/orders - Get all orders (admin only).
-GET /api/orders/:id - Get an order by ID.

**Repairs:**
-POST /api/repairs - Book a repair service.
-GET /api/repairs - Get all repair requests (admin only).
-PUT /api/repairs/:id - Update repair status (admin only).

---

# Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/YourFeatureName).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/YourFeatureName).
5. Open a pull request.

---

# License
  This project is licensed under the MIT License. See the LICENSE file for details.

---

# Contact
  *For any questions or feedback, feel free to reach out:
  *Email: ochiengpaul654@gmail.com
  *GitHub: Ochieng-001

---

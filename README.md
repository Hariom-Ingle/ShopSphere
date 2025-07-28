# 🛒 E-commerce Platform

This is a full-stack e-commerce application designed for modern online shopping experiences, utilizing cutting-edge technologies. The platform supports seamless user interaction, product management, secure payments, and analytics.

## 📽️ Demo

Watch the live demo here: [Click to Watch](https://youtu.be/UTScrFvI8ys)


 


![Your paragraph text (7)](https://github.com/user-attachments/assets/b37dc4c4-07b7-4ca0-a197-87d603f3228d)
## 🚀 Tech Stack


-  ⚛️ **Frontend**: React.js
-  🌐 **Backend**: Node.js (Express) 
-  🍃 **Database**: MongoDB 
-  ☁️ **Image Storage**: Cloudinary 
-  💳 **Payment Gateway**: Stripe  
-  🏎️ **In-memory Cache**: Redis  
-  📊 **Data Visualization**: Recharts  

## ✨ Key Features

- 🔑 **User Authentication**: Sign up, login, password management
- 🛍️ **Product Management**: Add, edit, remove products
- 💰 **Payment Processing**: Integrated with Stripe for secure transactions
- 📸 **Image Handling**: Upload and store product images via Cloudinary
- ⚡ **Performance**: Caching with Redis to enhance performance
- 📈 **Analytics**: Real-time data visualization with Recharts
- 📦 **Order Management**: Track and manage orders efficiently

## 🛠️ Installation Guide

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) 🟢
- [MongoDB](https://www.mongodb.com/) 🍃
- [Redis](https://redis.io/) 🏎️

### Steps to Set Up

1. **Clone the repository** :

   ```bash
   git clone https://github.com/Hariom-Ingle/e-commerce-store
   cd ecommerce-project

2. **Install server dependencies** :

    ```bash
    cd server
    npm install

3. **Install client dependencies** :

    ```bash
    Copy code
    cd ../client
    npm install
4. **Environment Variables** :

    Create a .env file in the root of the server folder and add:

    ```bash
    
    MONGODB_URI=<your-mongodb-uri>
    CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
    CLOUDINARY_API_KEY=<your-cloudinary-api-key>
    CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
    STRIPE_SECRET_KEY=<your-stripe-secret-key>
    REDIS_URL=<your-redis-url>

5.**Start the application**:

- Backend:

    ```bash
    
    cd server
    npm run dev
- Frontend:

    ```bash
 
    cd ../client
    npm start

🎉 Access the App: Open your browser and visit http://localhost:3000.


📄 License
This project is licensed under the MIT License.

 
 

 

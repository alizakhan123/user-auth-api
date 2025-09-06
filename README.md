# User Authentication System

A simple Node.js + Express + MongoDB based User Authentication System with signup and login functionality.

## Features
- User Registration & Login  
- Password Hashing with bcrypt  
- MongoDB Integration  

## How to Run

1. Clone the repository:

   git clone https://github.com/your-username/user-auth.git
   
   cd user-auth

3. Install dependencies:
   
   npm install

5. Create a .env file in the root folder and add your MongoDB connection:

   Example:
   
   MONGO_URI=mongodb://localhost:27019/users
   
   PORT=5000

👉 If you are using MongoDB Atlas, replace it with your own URL:


     MONGO_URI=mongodb+srv://<username>:<password>@cluster-url.mongodb.net/users


     PORT=5000

4. Start the server:

    npm start

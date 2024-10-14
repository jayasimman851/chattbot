
This is a Node.js-based chatbot application that uses Express, Mongoose, and Pug for building a web-based chatbot interface with a backend connected to MongoDB.

Features:
Chatbot Integration: Communicates with users via an API.
Express Framework: A minimal and flexible Node.js web application framework.
MongoDB Integration: Stores and retrieves data using Mongoose for MongoDB.
Dynamic Templating: Uses Pug as the templating engine for rendering views.
Static File Serving: Serves static assets like CSS and JavaScript from the public directory.
RESTful API: Provides an API endpoint for chatbot-related operations (/api/chatbot)

Technologies Used :
Node.js: Backend runtime environment.
Express: Web framework for Node.js.
Mongoose: ODM for MongoDB.
MongoDB: NoSQL database for storing chatbot data.
Body-parser: Middleware for parsing JSON request bodies.
dotenv: For loading environment variables from .env file.

Installation and Setup :
Prerequisites:
Node.js installed
MongoDB instance or MongoDB Atlas account
Git

Steps to Run the Project Locally:

Clone the Repository:
git clone https://github.com/your-username/chatbot-app.git
cd chatbot-app

Install Dependencies:
npm install
Set Up Environment Variables Create a .env file in the root directory and add your MongoDB connection string and other variables:

makefile:
MONGO_URI=your-mongodb-connection-string
PORT=3000

Run the Application
npm start
The application will start at http://localhost:3000.

API Endpoints:
GET /api/chatbot: Fetch the chatbot data.
POST /api/chatbot: Send user messages to the chatbot.

Screenshots:
![Screenshot 2024-10-14 221955](https://github.com/user-attachments/assets/e62765a4-c66e-4f3b-948c-425e78e4cf97)





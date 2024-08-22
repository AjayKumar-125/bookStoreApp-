
BookStoreApp is a web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application allows users to browse, search, and purchase books. It includes features like user authentication, a shopping cart, and an admin panel to manage books and orders.
Features:
-User Authentication: Secure login and registration for users.
-Book Browsing: Search for books by title, author, or genre.
-Responsive Design: Optimized for both desktop and mobile devices.
-Styled with Tailwind CSS & Daisy UI: Provides a modern and customizable UI.
Installation
Prerequisites
Make sure you have the following installed on your system:
Node.js
MongoDB
Clone the Repository
git clone https://github.com/AjayKumar-125/BookStoreApp.git
cd BookStoreApp
Install Dependencies
For the backend:
cd backend
npm install
For the frontend:
cd ../frontend
npm install
Environment Variables
Create a .env file in the backend directory and add the following environment variables:
MONGO_URI=<your_mongodb_connection_string>
JWT_SECRET=<your_jwt_secret_key>
Run the Application
To run the backend server:
cd backend
npm run dev
To run the frontend:
cd frontend
npm start

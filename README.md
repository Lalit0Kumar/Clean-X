# Project Configuration for Clean X: An Online Laundry Platform

Clean X is an online laundry platform designed to offer convenient and efficient laundry services. The application leverages the MERN stack (MongoDB, Express.js, React.js, Node.js) to provide a seamless user experience from both the frontend and backend.

# Frontend Configuration

--> Technologies Used:
React.js: For building the user interface.
Redux: For state management.
Axios: For making HTTP requests to the backend.
React Router: For handling routing within the application.

# Setting Up the Frontend:

1. Install Dependencies
   --> cd cleanx-frontend
   --> npm install
2. Project Structure

cleanx-frontend/
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ ├── redux/
│ ├── App.js
│ ├── index.js
│ ├── ...
├── .env
├── package.json
└── ...

3. Running the Frontend:
   --> npm start

# Backend Configuration

--> Technologies Used:
Node.js: For the server-side runtime environment.
Express.js: For building the server and API endpoints.
MongoDB: As the database to store user and laundry data.
Mongoose: For interacting with MongoDB.
JWT: For authentication and authorization.
dotenv: For managing environment variables.

1. Install Dependencies
   --> npm install

2. Project Structure

cleanx-backend/
├── controllers/
├── models/
├── routes/
├── middleware/
├── .env
├── server.js
├── package.json
└── ...

3. Environment Variables: Create a .env file in the root directory of your backend project.
   --> Exaples
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/cleanx
   JWT_SECRET=your_jwt_secret_key
   EMAIL=your_email@example.com
   PASS=your_password

4. Running the Backend
   --> npm run dev

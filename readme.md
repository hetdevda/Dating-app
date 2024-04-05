
### Frontend Readme for Senior Tinder

This is the frontend repository for Senior Tinder, a web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. Senior Tinder is a platform where users can connect with other users, browse profiles, and potentially form matches to chat with each other.

#### Usage

1. Start the development server: `npm start`
2. Access the application in your browser at `http://localhost:3000`

#### Features

- User Registration and Login: Users can register for an account and login to the application.
- Profile Activation: Users can upload 2 images to activate their account.
- Profile Browsing: Users can browse other users' profiles based on filters like age and gender.
- Like/Unlike Profiles: Users can like or unlike other users' profiles.
- Matching: If two users like each other's profiles, they become a match and can chat with each other.

#### Technologies Used

- React.js: Frontend framework for building the user interface.
- Axios: HTTP client for making requests to the backend API.
- SCSS: Frontend framework for styling the application.

#### Folder Structure

- `src/components`: Contains reusable components used throughout the application.
- `src/pages`: Contains the main pages of the application (e.g., Home, Login, Register).



### Backend Readme for Senior Tinder

This is the backend repository for Senior Tinder, a web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. Senior Tinder is a platform where users can connect with other users, browse profiles, and potentially form matches to chat with each other.

#### Configuration

1. Create a `.env` file in the root directory of the project.
2. Add the following environment variables to the `.env` file:
  PORT=4000
  MONGODB_URI=<your-mongodb-uri>


#### Database Setup

1. Ensure that MongoDB is installed and running on your local machine or use a MongoDB service like MongoDB Atlas.
2. Update the `MONGODB_URI` environment variable in the `.env` file with your MongoDB connection URI.

#### Usage

1. Start the server: `npm start`
2. The server will start at `http://localhost:4000`

#### Technologies Used

- Node.js: Backend runtime environment for running JavaScript code.
- Express.js: Backend framework for building the API.
- MongoDB: NoSQL database for storing user profiles and chat messages.
- Mongoose: MongoDB object modeling library for Node.js.

#### Folder Structure

- `config`: Contains configuration files for the server (e.g., database, JWT).
- `controllers`: Contains controller functions for handling API requests.
- `models`: Contains Mongoose models for defining the database schema.
- `routes`: Contains route definitions for the API endpoints.
- `middleware`: Contains middleware functions for authentication and error handling.

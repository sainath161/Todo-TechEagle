# ToDo Application

Welcome to the ToDo application! This project provides a simple yet effective way to manage your daily activities with a clean and intuitive interface. It consists of both backend and frontend components to handle user authentication, activity management, and more.

### Features

    User Authentication: Register and login securely to manage your activities.
    Activity Management: Add, view, update, and delete activities with ease.
    Activity Status Tracking: Track the status of each activity (Pending, Ongoing, Paused, Completed).
    Activity History: View detailed history of actions (Start, Pause, Resume, End) for each activity.
    Responsive Design: User-friendly interface that adapts to different screen sizes.

### Technologies Used

#### Frontend:
        React.js
        React Router
        Axios for API requests
        Context API for state management
        CSS for styling

#### Backend:
        Node.js
        Express.js
        MongoDB Atlas for database
        Mongoose for ODM
        JWT for authentication

### Getting Started

To get a local copy up and running follow these simple steps.
Prerequisites

    Node.js installed on your local machine
    MongoDB Atlas account for database (or local MongoDB setup)

### Installation

#### Clone the repo

git clone https://github.com/sainath161/https://github.com/sainath161/Todo-TechEagle.git

#### Install NPM packages

npm install

#### Set up environment variables

    Create a `.env` file in the root of the backend directory (todo-backend/.env) and add the following variables:

    PORT=5000
    MONGO_URI=<your_mongodb_uri>
    JWT_SECRET=<your_jwt_secret>

    Replace <your_mongodb_uri> with your MongoDB connection URI and <your_jwt_secret> with a secret key for JWT.

#### Start backend server

npm run dev

#### Start frontend development server

npm start

### API Endpoints

    GET /api/activities - Get all activities for the authenticated user
    POST /api/activities - Create a new activity
    PUT /api/activities/:id - Update the status of an activity
    GET /api/activities/:id - Get details of a specific activity
    POST /api/users/register - Register a new user
    POST /api/users/login - Login existing user

## Deployment

Ckeck out the project demo [here](https://todo-techeagle.onrender.com)
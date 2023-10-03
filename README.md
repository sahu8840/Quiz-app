# Language Learning Game (MERN Stack)

Welcome to the Language Learning Game assignment! This project is built using the MERN (MongoDB, Express, React, Node.js) stack, and it is organized into two main folders: `client` and `server`. Each folder contains relevant code and components for the frontend and backend, respectively.

## Project Structure

### Client

Inside the `client` folder, you'll find the following structure:

- `index.js`: The entry point for the React application.
- `components`: This folder contains React components that make up the frontend UI.
- `helper`: Here, you can find utility functions or helper code that supports the frontend.
- `hooks`: Custom React hooks can be found in this folder.
- `redux`: Redux-related code and state management are organized in this directory.
- `styles`: CSS or styling files for the frontend components.

### Server

Inside the `server` folder, you'll find the following structure:

- `server.js`: The entry point for the Node.js and Express application.
- `controllers`: This folder contains controllers that handle routes and logic.
- `databases`: Here, you can find database configurations and setup.
- `models`: Database models and schemas are defined in this directory.
- `router`: Express routes and API endpoints are organized here.

## Getting Started

To set up and run the Language Learning Game project locally, follow these steps:

1. **Client Setup**:
   - Navigate to the `client` folder.
   - Install the frontend dependencies by running:

     ```bash
     cd client
     npm install
     ```

   - Start the React development server:

     ```bash
     npm start
     ```

   The client-side application should now be running and accessible at `http://localhost:3000`.

2. **Server Setup**:
   - Navigate to the `server` folder.
   - Install the backend dependencies by running:

     ```bash
     cd server
     npm install
     ```

   - Start the Node.js server:

     ```bash
     npm start
     ```

   The server should now be running and accessible at `http://localhost:5000`.

3. **Database Configuration**:
   - Used Mongodb atlas and provided the appropriate database connection details in the server configuration files.

4. **Configure Environment Variables**:
   - Created `.env` file in the server as well as in client directory to store configuration settings.

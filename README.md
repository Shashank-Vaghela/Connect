# MERN Chat Application

# Connect

Connect is a modern chat application designed to provide a seamless communication experience. With features like real-time messaging, file sharing, group creation, and notifications, Connect makes staying in touch easy and efficient.

## Features

- **Real-time Messaging**: Instant messaging with real-time updates.
- **File Sharing**: Send and receive any type of file.
- **Infinite Scrolling**: Smooth and continuous scrolling experience.
- **Sign In/Sign Up**: Secure authentication system.
- **Group Chats**: Create and manage chat groups.
- **Friend Requests**: Add and manage your friends.
- **Admin Dashboard**: Admin functionalities to manage users and groups.

## Tech Stack

- **MongoDB**: Database for storing user data, messages, and files.
- **Express.js**: Web framework for building the backend APIs.
- **Node.js**: JavaScript runtime for the server-side logic.
- **React.js**: Frontend library for building the user interface.
- **Socket.IO**: Real-time communication between the client and server.

## Prerequisites

Before running the application, ensure you have the following installed:

- Node.js and npm (Node Package Manager)
- MongoDB (Optional) (Make sure MongoDB is running on your machine or accessible via a MongoDB URI). If you use my MongoDB URI then you won't need this.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```
   git clone https://github.com/Shashank-Vaghela/connect.git
   cd connect
   ```

2. **Set up environment variables: Create a .env file in the root directory and add the following variables**:


- **MONGO_URI=your_mongodb_connection_string**
- **JWT_SECRET=your_jwt_secret_key**
- **NODE_ENV=DEVELOPMENT**
- **CLIENT_URL='http://localhost:5173/'**
- **CLOUDINARY_CLOUD_NAME=your_cloud_name**
- **CLOUDINARY_API_KEY=your_cloud_api_key**
- **CLOUDINARY_API_SECRET=your_cloud_api_secret**

3. **Install dependencies**:

   For client:
   ```
   cd Client
   npm install
   ```

   For Server:
   ```
   cd Server
   npm install
   ```

4. **Running the Application**

   ### Client (React Frontend)
   
   1. Navigate to the Client directory:
   ```
   cd Client
   ```

   2. Start the React development server:
   ```
   npm run dev
   ```

   The client will run on `http://localhost:5173/`.

   ### Server (Node.js/Express Backend)

   1. Navigate to the Server directory:
   ```
   cd Server
   ```

   2. Start the Node.js server:
   ```
   npm run dev
   ```

   The server will run on `http://localhost:3000` and will output:
   ```
   Server is running on port 3000 in DEVELOPMENT Mode
   Connected to DB
   ```

## Usage

Once both the client and server are running, open your web browser and visit `http://localhost:5173/` to use the chat application.
# Real_Time_Chat_App_Using_MERN

A real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js), Socket.io, TailwindCSS, and Daisy UI. The application features authentication and authorization using JWT, real-time messaging, online user status, global state management, and comprehensive error handling. The application is deployed on Render.

## Features

- **Authentication & Authorization**: Secure login and registration using JSON Web Tokens (JWT).
- **Real-time Messaging**: Instant messaging functionality powered by Socket.io.
- **Online User Status**: Real-time updates on user status using Socket.io and React Context.
- **Global State Management**: Efficient state management across the app with Zustand.
- **Responsive UI**: Styled with TailwindCSS and Daisy UI for a modern and responsive design.
- **Error Handling**: Robust error handling both on the server and client sides.

## Tech Stack

- **Frontend**: React, Vite, TailwindCSS, Daisy UI
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Real-time Communication**: Socket.io
- **State Management**: Zustand
- **Authentication**: JWT

![Screenshot 2024-06-14 001553](https://github.com/amitesh197/Real_Time_Chat_App_Using_MERN/assets/123076729/75d4d30a-cb94-4265-a165-f837addafa30)
![Screenshot 2024-06-14 001600](https://github.com/amitesh197/Real_Time_Chat_App_Using_MERN/assets/123076729/2c5f0294-d3f0-437a-9c13-b7809e71eef5)
![Screenshot 2024-06-14 001705](https://github.com/amitesh197/Real_Time_Chat_App_Using_MERN/assets/123076729/766ec572-22cf-484c-bc79-45a5eeeaa0ac)


## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/amitesh197/Real_Time_Chat_App_Using_MERN.git
    ```

2. **Environment Variables:**
   Create a `.env` file in the root directory and add the following environment variables:
    ```env
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    PORT=your_socket_port
    NODE_ENV=development
    ```

3. **Build the project:**
    ```bash
    npm run build
    ```

4. **Start the project:**
    ```bash
    npm start
    ```


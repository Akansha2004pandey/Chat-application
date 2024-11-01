
# Chat App - ChitChat

The Chat Application is a real-time messaging platform that allows users to communicate seamlessly through text-based messages. Built using modern web technologies, the app features a user-friendly interface for an enhanced chat experience. Users can register, log in and privately chat with multiple people.


Tech Stack
Frontend:

React: A JavaScript library for building user interfaces, allowing for a dynamic and responsive user experience.
Socket.IO-client: Enables real-time bidirectional event-based communication between the client and server.
Axios: For making HTTP requests to the backend API.
Tailwind CSS: A utility-first CSS framework for styling the application and ensuring a modern, responsive design.

Backend:

Node.js: A JavaScript runtime for building scalable network applications.
Express: A minimal and flexible Node.js web application framework for building RESTful APIs.
Socket.IO: Facilitates real-time communication between users in the chat application.
MongoDB: A NoSQL database for storing user data, chat rooms, and messages.
Mongoose: An ODM (Object Data Modeling) library for MongoDB and Node.js, used to manage relationships between data and provide schema validation.
Authentication:

JWT (JSON Web Tokens): Used for secure user authentication and authorization, ensuring that user sessions are protected.

## Documentation

[Express.js](https://expressjs.com/) |
[React.js](https://react.dev/) |
[Json Web Token](https://jwt.io/)



## Environment Variables

To run this project, you will need to add the following environment variables to your .env file
`PORT` | 
`MONGO_URI` |
`JWT_SECRET_KEY`


## Features

1. User Registration and Login: Allow users to create accounts and securely log in to access chat functionalities.
2. Real-Time Messaging: Enable instant message delivery between users using Socket.IO for real-time communication.
3. Private Messaging: Option for users to send direct messages to one another outside of chat rooms.



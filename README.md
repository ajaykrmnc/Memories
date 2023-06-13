# [The Memories](https://we-amigos.netlify.app)
<img src="https://we-amigos.netlify.app/static/media/memories.9cfa8a4697e085d87136.png" width="150"/>

The Memories is a web application where users can share their images and write about their memories. It provides social media-like features such as liking posts and user authentication. This project is built using the MERN stack.

## Features

- User registration and authentication using Firebase
- Post creation, and deletion
- Post liking functionality
- User feed to display posts from other users
- Responsive and visually appealing UI

## Technologies Used

- MongoDB: Database for storing user data, posts, etc.
- Express.js: Web application framework for server-side logic and APIs.
- React.js: JavaScript library for building user interfaces.
- Node.js: JavaScript runtime environment for server-side code.
- Firebase: Authentication service for user registration and login.

## Deployment

- Frontend: The client-side of this application is deployed on [Netlify](https://www.netlify.com/) and can be accessed at [we-amigos.netlify.app](https://we-amigos.netlify.app).

- Backend: The server-side is deployed on [Render](https://render.com/).

## Prerequisites

Before running the application, ensure you have the following installed:

- Node.js (v14 or above)
- MongoDB (make sure it's running)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/the-memories.git
   ```

2. Install the dependencies for both the server and the client:

   ```bash
   cd the-memories
   npm install
   cd client
   npm install
   cd ..
   ```

3. Set up the environment variables:

   - Create a `.env` file in the root directory.
   - Add the required environment variables (such as Firebase credentials, MongoDB connection string, etc.).

4. Run the application:

   ```bash
   # Run server and client concurrently
   npm run dev
   ```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to access the application.

## Contributing

Contributions are welcome! If you find any issues or want to suggest enhancements, please create a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
```

Make sure to replace "your-username" with your actual GitHub username and update any other necessary information based on your project setup.

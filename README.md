
# Project-Wanderlust

This project, developed on a local system, is a comprehensive Full Stack application utilizing MERN (MongoDB, Express.js, React, Node.js) technology. The primary goal of this project is to create a global directory of hotels across various cities, making it easier for users to find and access accommodations for their vacation destinations.
 
#  Frontend:
 HTML5 / CSS3 / JAVA SCRIPT

# Backend:
1. NODE.JS
2. EXPRESS.JS

# Database:
1. MONGO-DB

# Framework
1. BOOTSTRAP

# Other
  This project is built with the MVC Framework, REST APIs, and AJAX as part of its implementation.

  # Deployed Link
 https://wanderlust-gprt.onrender.com/listings
  
# Wanderlust Web Project Installation Guide

This guide will walk you through the installation process for the Wanderlust web project. Follow the steps below to set up the project locally on your machine.

## Prerequisites

Make sure the following are installed on your system before you proceed:

- Node.js (version 18 recommended)
- MongoDB
- Nodemon (installed globally)

## Installation Steps

1. Retrieve the Wanderlust repository from GitHub by cloning it:

   ```
   https://github.com/Rajsinghh2907/WanderLust/tree/master
   ```

2. Initialize the database:

Generate a .env file in the root directory of your project.
Include the following line in the .env file:

     ```
     ATLASDB_URL=mongodb://127.0.0.1:27017/wanderlust
     ```

3. Configure Cloudinary:
   Navigate to [Cloudinary](https://cloudinary.com/) and create a free account.
   After logging in, retrieve your Cloudinary `CLOUD_NAME`, `CLOUD_API_KEY`, and `CLOUD_API_SECRET`.
   Add these values to the `.env` file:

     ```
     CLOUD_NAME=your_cloud_name
     CLOUD_API_KEY=your_api_key
     CLOUD_API_SECRET=your_api_secret
     ```

4. Establish the secret for your Cloudinary storage:
   Add a `SECRET` key to your `.env` file and set it to a secure value:

     ```
     SECRET=your_cloudinary_secret
     ```

5. Install project dependencies using npm:

   ```
   npm install
   ```

6. Run the application using Nodemon:

   ```
   nodemon app.js
   ```

7. Access the project:
    Once the server is live, navigate to http://localhost:8080 to access the project.

You're all set! The Wanderlust web project is now installed and configured on your local machine. Should you run into any problems during installation, please feel free to ask for help. Enjoy your journey!

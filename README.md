# Real-Time Chat Application

A real-time chat application built with React for the frontend and Express for the backend. This application leverages [ChatEngine.io](https://chatengine.io/) for real-time messaging functionalities.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Features

- Real-time messaging using ChatEngine.io
- Responsive user interface built with React
- Scalable backend with Express

## Technologies

- **Frontend**: React
- **Backend**: Express
- **Real-time Messaging**: [ChatEngine.io](https://chatengine.io/)

## Prerequisites

Ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/)

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/deepanshunegi06/Real-time-chat-application.git
#Configuration
The application requires a ChatEngine.io API key for real-time messaging. Obtain an API key from ChatEngine.io and update your configuration files in both the frontend and backend directories with the new API key.

#Running the Application
To start the application, first, run the backend server. Navigate to the backend directory and execute npm start. Then, start the frontend server by navigating to the frontend directory and running npm run dev.

#Troubleshooting
If you encounter issues pushing to the remote repository, ensure the remote repository is set up correctly and you have the necessary permissions. Use git remote -v to verify the remote URL and use git push -f origin main to force push changes if needed. If you face issues with missing node modules, ensure you have run npm install in both frontend and backend directories.

#License
This project is licensed under the MIT License. For more details, see the LICENSE file.

# MERN AI Chat Bot

This project is a conversational AI Chat Bot built using the MERN stack (MongoDB, Express, React, Node.js). It provides interactive, intelligent responses to users' queries, making it ideal for use in customer support, personal assistants, and other interactive applications.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Available Scripts](#available-scripts)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Features
- Real-time chat interface with dynamic responses.
- Natural language processing for AI-driven responses.
- Scalable backend with MongoDB for data storage.
- Customizable UI for chat interactions.
- Easy setup and deployment.

## Tech Stack
- **Frontend**: React, HTML, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Development Environment**: Visual Studio Code

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vanditaa12/AI-Chat-Bot.git
   cd AI-Chat-Bot
   
## Available Scripts
In each project directory (`frontend` and `backend`), you can run the following commands:

### `npm start`
Starts the server (backend) or application (frontend) in development mode.

### `npm test`
Runs the test suite for the backend or frontend, respectively.

### `npm run build`
Builds the frontend for production to the `build` folder.

## Usage
Open [http://localhost:3000](http://localhost:3000) to use the AI Chat Bot in your browser. Type your queries and receive real-time responses based on the integrated NLP model.

## Project Structure

```plaintext
AI-Chat-Bot/
├── backend/              # Backend code
│   ├── models/           # Database models
│   ├── routes/           # API routes
│   ├── controllers/      # Route controllers
│   └── app.js            # Main server file
├── frontend/             # Frontend code
│   ├── public/           # Public assets
│   ├── src/              # Source files
│   │   ├── components/   # React components
│   │   ├── pages/        # Page components
│   │   └── App.js        # Main React component
└── README.md

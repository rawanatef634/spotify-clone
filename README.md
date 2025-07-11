﻿# spotify-clone
 
A modern, full-stack music streaming application inspired by Spotify, built with real-time features and a sleek user interface.

# Table of Contents
Features
Tech Stack
Installation
Usage
Environment Variables
Contributing
License

# Features
Real-time Music Streaming: Stream music with low latency using WebSocket integration.
User Authentication: Secure login and registration with JWT-based authentication.
Playlist Management: Create, edit, and share playlists.
Search Functionality: Search for songs, artists, and albums.
Responsive Design: Optimized for both desktop and mobile devices.
Music Player: Play, pause, skip, and control volume with a fully functional music player.
Real-time Updates: Get live updates for new releases and playlist changes.

# Tech Stack
Frontend: React, TypeScript, Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB
Real-time Communication: Socket.IO
Authentication: JSON Web Tokens (JWT)
Audio Streaming: Web Audio API
Deployment: Vercel (Frontend), Heroku (Backend)

# Installation
Clone the repository:
git clone https://github.com/rawanatef634/spotify-clone.git
cd spotify-clone


Install dependencies for both frontend and backend:
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install


Set up environment variables (see Environment Variables).

Start the development servers:
# Backend (from backend directory)
npm run dev

# Frontend (from frontend directory)
npm start


Open your browser and navigate to http://localhost:3000.


# Usage

Register or log in to access the application.
Browse or search for music to create playlists.
Use the music player to stream songs and control playback.
Share playlists with other users in real-time.

# Environment Variables
Create a .env file in the backend directory with the following variables:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
SPOTIFY_API_KEY=your_spotify_api_key

Create a .env file in the frontend directory with:
REACT_APP_API_URL=http://localhost:5000
REACT_APP_SOCKET_URL=http://localhost:5000

# Contributing
Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.

# License
This project is licensed under the MIT License. See the LICENSE file for details.


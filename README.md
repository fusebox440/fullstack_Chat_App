# Fullstack Chat App

A fullstack real-time chat application with a Node.js/Express backend and a Vite + React frontend.

## Features
- User authentication
- Real-time messaging with Socket.IO
- User list and chat UI
- Responsive layout

## Tech Stack
- Backend: Node.js, Express, MongoDB, Socket.IO
- Frontend: React, Vite, Tailwind CSS

## Project Structure
```
backend/   # API, DB, sockets
frontend/  # React client
```

## Getting Started

### 1) Backend
```bash
cd backend
npm install
npm run dev
```

### 2) Frontend
```bash
cd frontend
npm install
npm run dev
```

## Environment Variables
Create a `backend/.env` file with the following values:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
CLIENT_URL=http://localhost:5173
```

## Scripts
- Backend: `npm run dev`
- Frontend: `npm run dev`

## License
MIT

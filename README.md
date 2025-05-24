# Opinions Forum

A React application where users can share their opinions and vote on them. Built with React, Vite, and uses a JSON-server backend for data persistence.

## Features

- Create and share opinions
- Upvote and downvote opinions
- Real-time sorting based on votes
- Simple and intuitive interface

## Prerequisites

- Node.js (v14 or higher)
- npm

## Setup Instructions

1. Clone the repository

2. Install frontend dependencies
```bash
npm install
```

3. Install backend dependencies
```bash
cd backend
npm install
cd ..
```

## Running the Application

1. Start the backend server
```bash
cd backend
npm start
```
This will start the JSON server on http://localhost:3000

2. In a new terminal, start the frontend development server
```bash
npm run dev
```
This will start the Vite development server on http://localhost:5173

## Project Structure

- `frontend/`: React application built with Vite
  - `src/components/`: React components
  - `src/store/`: Context providers and state management
- `backend/`: JSON-server implementation
  - `db.json`: Database file
  - `app.js`: Server configuration

## Technologies Used

- React
- Vite
- JSON-server
- React Context API
- CSS

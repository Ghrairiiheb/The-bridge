﻿# The-Bridge- E-learning Platform 
# Description
The Bridge is an e-learning platform designed to help users enhance their skills and prepare for a better future. The application provides course listings, registration options, and an intuitive user interface for exploring learning opportunities.

## Features
- Hero section with call-to-action buttons for registration.
- Course discovery section with navigation options.
- Admin page for adding, deleting, and updating courses.
- Responsive design using Chakra UI components.
- Dynamic content fetching using React hooks and state management.
- Backend integration with MongoDB for data storage and management.
- API services built using Node.js and Express.js.

## Technologies Used
### Frontend:
- **React.js** - Front-end framework for building user interfaces.
- **Vite.js** - Development environment for fast builds and optimized performance.
- **Chakra UI** - Component library for styling and layouts.
- **JavaScript (ES6)** - Core language for interactivity and logic.

### Backend:
- **Node.js** - JavaScript runtime for server-side development.
- **Express.js** - Framework for building web APIs.
- **MongoDB** - NoSQL database for storing course and user data.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/the-bridge.git
   ```
2. Navigate to the project directory:
   ```bash
   cd the-bridge
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up the environment variables:
   Create a `.env` file with the following:
   ```plaintext
   MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/database_name
   PORT=6000
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

## Usage
- Open the application in your browser at `http://localhost:5173`.
- Browse courses and register for your preferred options.
- Access the admin page for managing courses (add, delete, update).

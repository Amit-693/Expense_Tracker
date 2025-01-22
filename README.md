# Expense_Tracker
description about expense tracker  

## Table of Contents

- [Features](#features)
- [Frontend](#frontend)
- [Backend](#backend)
- [API Endpoints](#api-endpoints)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Authentication](#authentication)
- [License](#license)

## Features

- Store various types of income options.
- Dashboard visualizing expenses. 
- User authentication and profile management.
- Responsive and user-friendly interface.

## Frontend

The client-side application is served on localhost:3000.

### Links

- *Home:* / or /home
- *Login:* /login
- *Signup:* /signup
- *Profile:* /profile:id


## Backend

The server-side application is served on localhost:3000.

## API Endpoints

### /api/notes/

1. *GET /*
   - Fetch all transactions.

2. *POST /*
   - To add of transactions.

3. *POST '/login'*
   - To login an existing user.

4. *POST /signup*
   - Register new user.

5. *DELETE /:expenseId*
   - To delete any selected transactions.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. *Clone the repository:*

    bash
    git clone <repository-url>
    

2. *Navigate to the project directory:*

    bash
    cd NoteWave
    

3. *Install dependencies for both frontend and backend:*

    bash
    cd frontend
    npm install
    cd ../backend
    npm install
    

4. *Set up environment variables:*

    Create a .env file in the backend directory and add your environment variables. Example:

    env
    PORT=3000
    MONGODB_URI=<your-mongodb-uri>
    

5. *Start the development servers:*

    bash
    cd frontend
    npm start
    cd ../backend
    npm run dev
    

## Dependencies

### Frontend

- @reduxjs/toolkit: ^2.2.5
- axios: ^1.7.2
- boxicons: ^2.1.4
- react: ^18.2.0
- react-dom: ^18.2.0
- react-redux: ^9.1.2
- react-router-dom: ^6.23.1

### Backend

 "bcrypt": "^5.1.1",
    "body-parser": "^1.20.2",
    "cors": "^2.8.5",
    "dotenv": "^16.4.5",
    "express": "^4.19.2",
    "joi": "^17.13.1",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^8.4.1

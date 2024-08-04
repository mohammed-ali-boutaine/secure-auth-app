

# Secure Auth App

A secure authentication app built with Express, MongoDB, EJS, and Passport.js. This app provides a robust foundation for implementing user authentication with session management and password hashing.

## Features

- User registration and login
- Password hashing with bcrypt
- Session management with express-session
- Authentication with Passport.js
- Protected routes
- EJS templating

## Technologies

- Node.js
- Express
- MongoDB
- Mongoose
- EJS
- Passport.js
- bcrypt

## Installation

1. Clone the repository:
```bash
   git clone https://github.com/yourusername/secure-auth-app.git
   cd secure-auth-app
```

2. Install dependencies:

```bash
  npm install
```
3. Set up environment variables:

Create a .env file in the root of the project and add the following variables:

```bash
  PORT=3000
  MONGO_URI=your_mongo_db_connection_string
  SESSION_SECRET=your_session_secret
  NODE_ENV=development

```

4. Start the application:

```bash
  npm run dev

```
5. Open your browser and visit `http://localhost:3000`.

## Usage

Register a new user at /register.
Login with the registered user at /login.
Access the protected route /secrets after logging in.
Logout at /logout.

## Project Structure
```bash
secure-auth-app/
├── models/
│   └── User.js
├── public/
│   └── ...
├── views/
│   ├── home.ejs
│   ├── login.ejs
│   ├── register.ejs
│   └── secrets.ejs
├── .env
├── .gitignore
├── package.json
├── README.md
└── server.js
```

## Acknowledgements:

- Express
- MongoDB
- EJS
- Passport.js
- bcrypt


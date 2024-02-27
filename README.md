# Login and SignUp System with User Authentication

A simple Node.js and Express.js application with user authentication using MongoDB.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Features

- User registration with password hashing (bcrypt).
- User login with session-based authentication.
- MongoDB for data storage.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/sithuminikaushalya/Login-and-SignUp-System-with-User-Authentication-Using-Node-Js-Express-Js-MongoDB.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Login-and-SignUp-System-with-User-Authentication-Using-Node-Js-Express-Js-MongoDB
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Set up your MongoDB connection:

    - Create a `.env` file in the project root.
    - Add the following line, replacing `<your-mongodb-uri>` with your MongoDB connection URI:

        ```env
        MONGODB_URI=<your-mongodb-uri>
        ```

5. Start the application:

    ```bash
    npm start
    ```

## Usage

1. Visit [http://localhost:3001](http://localhost:3001) in your browser.
2. Register a new account or log in.
3. Explore the user authentication features.




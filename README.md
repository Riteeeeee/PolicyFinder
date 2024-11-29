# PolicyFinder# PolicyFinder

PolicyFinder is a web application that helps users find the correct policy based on their personal data such as occupation, age, gender, caste, and income. The application is built using Node.js as the backend, MongoDB as the database, and JWT (JSON Web Token) for authentication.

## Features

- User authentication using JWT tokens.
- Database storage and retrieval using MongoDB.
- Policy recommendation based on user data.
- User-friendly web interface.

## Prerequisites

Before running the PolicyFinder application, ensure you have the following prerequisites installed on your system:

- Node.js: [Download and install Node.js](https://nodejs.org) for your operating system.
- MongoDB: [Download and install MongoDB](https://www.mongodb.com/try/download/community) for your operating system.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/policyfinder.git
   ```

2.Change to the project's root directory:
   ```shell
cd policyfinder
```
3.Install the dependencies:
   ```shell
npm install
```
4.Create a .env file in the project's root directory and specify the following environment variables:
   ```shell
PORT = <port no.>
MONGODB_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
EMAIL_HOST = <your-host-email>
EMAIL_PORT = 587
EMAIL_USER = <your email_id>
EMAIL_PASS = <email_password>
EMAIL_FROM = <your email_id>
```
Replace <your-mongodb-uri> with the connection URI for your MongoDB database and <your-jwt-secret> with a secret key for JWT token encryption.

Start the application:
   ```shell
npm run start
```
The application will be accessible at http://localhost:PORT.

## Usage
-Open a web browser and navigate to http://localhost:PORT.
-Register a new user account or log in using existing credentials.
-Fill in your personal details such as occupation, age, gender, caste, and income.
-Submit the form to receive policy recommendations based on your data.

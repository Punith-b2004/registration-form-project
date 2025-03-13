## Registration Form with Node.js and MongoDB

## Description
This project is a simple **Registration Form** built with HTML, CSS, and Bootstrap for the frontend, and Node.js with Express and MongoDB for the backend. Users can fill out the form to sign up, and their data is stored in a MongoDB database.

## Features
## User-friendly registration form with fields for **name, age, email, phone number, gender, and password**.
## Data validation to ensure required fields are filled.
## Backend powered by **Node.js and Express.js**.
## Uses **MongoDB** for storing user data.
## Simple success redirection after successful registration.

## Technologies Used
## Frontend
## **HTML**
## **CSS**
## **Bootstrap 5.3.3**

## Backend
## **Node.js**
## **Express.js**
## **MongoDB**
## **Mongoose**
## **Body-parser**

## Installation & Setup
## Prerequisites
Make sure you have the following installed:
## [Node.js](https://nodejs.org/)
## [MongoDB](https://www.mongodb.com/)

## Steps to Run
## 1. Clone the repository:
```sh
git clone https://github.com/Punith-b2004/registration-form-projec.git
cd registration-form
```

## 2. Install dependencies:
```sh
npm install
```

## 3. Start MongoDB (if not running already):
```sh
mongod
```

## 4. Run the server:
```sh
node server.js
```

## 5. Open your browser and go to:
```
http://localhost:3000/
```



## API Routes
| Route      | Method | Description |
|------------|--------|-------------|
| `/`        | GET    | Serves the registration page |
| `/sign_up` | POST   | Handles user registration and stores data in MongoDB |

## Future Enhancements
## Add **password hashing** for better security.
## Implement **email verification** for user authentication.
## Improve **UI design** with additional styling.



## License
## This project is open-source and available under the [MIT License](LICENSE).


# 🏨 My Hotel Booker - Express API

## Description

Welcome to the API repo of My Hotel Booker! 🎉

This API serves as the backend for the [My Hotel Booker](https://github.com/gabrielgonta/MyHotelBooker.git) Frontend, providing a robust and scalable solution for managing hotel bookings, user accounts, and more. Built with Express.js and integrated with MySQL via Sequelize, this project ensures a seamless experience for hotel booking applications.

## Prerequisites

Before running MyHotelBookerAPI, ensure you have the following installed:

Node.js (v16 or later recommended)

MySQL

Git

Postman (For testing API endpoints)

You can install NodeJs : https://nodejs.org/fr/

## Installation

Clone the repository :

```
git clone https://github.com/gabrielgonta/MyHotelBookerAPI.git
```

Navigate to the root directory where the 'package.json' file is located, then run the command to install the dependencies :

```
cd MyHotelBookerAPI
npm install
```

## Database Setup

Ensure MySQL is installed and running. Create the necessary databases:

```
CREATE DATABASE myhotelbooker_prod;
CREATE DATABASE myhotelbooker_test;
```

## Environment Configuration

Copy ```.env.example``` to ```.env``` and update it with your database credentials and JWT secret:

```
# Development Environment
DEV_DB_HOST=localhost
DEV_DB_USER=yourusername
DEV_DB_PASS=yourpassword
DEV_DB_NAME=myhotelbooker_test

# Production Environment
PROD_DB_HOST=localhost
PROD_DB_USER=yourusername
PROD_DB_PASS=yourpassword
PROD_DB_NAME=myhotelbooker_prod

# JWT Secret
JWT_SECRET=your_jwt_secret
```

## Running the API

Once everything is set up, start the development server:

```
npm run start:dev
```

By default, the API runs on http://localhost:3000/ :

## How I try to stand out

        ✔️ Express.js & Sequelize - Fast, efficient, and scalable backend.
        ✔️ MySQL Database - Reliable relational database for structured data management.
        ✔️ JWT Authentication - Secure user authentication with JSON Web Tokens.
        ✔️ Environment Configuration - Easily configurable via .env file.
        ✔️ API Testing with Postman - Simplified testing for all API endpoints.
        ✔️ Sequelize ORM - Database interaction made easy.

## API Testing with Postman

To test API endpoints, use Postman. If available, import the provided Postman collection to quickly start testing functionalities like:

User Authentication

Hotel Listings

Bookings Management

## Sequelize & MySQL Integration

This project uses Sequelize, a promise-based Node.js ORM, to interact with MySQL efficiently.

Database Configuration: Located in ```config/config.js```

Models: Defined in the ```models``` directory

## Contributing

Contributions are welcome! If you find bugs, have feature suggestions, or want to improve the documentation:

Open an issue

Submit a pull request

## Code Quality

Maintaining high code quality is a priority. Before submitting a PR, please ensure:

Code follows best practices.

Changes are well-tested.

The implementation is clear and maintainable.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Authors

* **Gabriel Gonta** - *Initial work* - [MyHotelBookerAPI](https://github.com/gabrielgonta/MyHotelBookerAPI.git)
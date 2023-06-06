# Back-End-Ecommerce

## Description

Back-End-ECommerce is an Express.js API that utilizes Sequelize as an ORM (Object-Relational Mapping) tool for connecting to a MySQL database. The API provides various routes for managing categories, products, and tags.

## Installation

To install and run the Express.js API, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies by running the following command: npm install
4. Create an environment variable file (e.g., .env) in the root directory of the project.
5. Open the environment variable file and add the following variables: 

* DB_NAME=your_database_name
* DB_USER=your_mysql_username
* DB_PASSWORD=your_mysql_password

Replace your_database_name, your_mysql_username, and your_mysql_password with your actual MySQL database credentials.

6. Save the environment variable file (.env).

## Building Blocks

This project utilizes the following technologies and libraries:

* Express.js: A fast and minimalist web application framework for Node.js.
* Sequelize: A powerful ORM for Node.js that supports multiple database systems, including MySQL.
* MySQL: A popular open-source relational database management system.
* Insomnia Core: A cross-platform REST API client for testing API endpoints.

## Usage

Follow the steps below to set up and use the Express.js API project:

1. Ensure that you have completed the installation steps mentioned earlier.

2. Open a terminal or command prompt and navigate to the project directory.

3. Run the following command to create the development database and seed it with test data:

npx sequelize-cli db:create
npx sequelize-cli db:migrate
npx sequelize-cli db:seed:all

4. Once the database is created and seeded, start the server by running the following command: npm start

5. Use a tool like Insomnia Core or any other API testing tool to interact with the API endpoints.

* For GET routes, use the following routes in Insomnia Core to retrieve data:

- GET /categories - Retrieves all categories.
- GET /products - Retrieves all products.
- GET /tags - Retrieves all tags.

* The data for each route will be returned in a formatted JSON response.

* For POST, PUT, and DELETE routes, use the corresponding routes in Insomnia Core to create, update, and delete data in the database.

![Viewing Products](./Images/Viewing%20Products.png)
![Viewing Categories](./Images/Viewing%20Categories.png)
![Viewing Tags](./Images/Viewing%20Tags.png)

[Walkthrough Video](https://photos.app.goo.gl/vRjuCLDKe4QBCZEUA)

## Features

This Express.js API project provides the following features:

1. Connection to a MySQL database using Sequelize as an ORM tool.
2. Creation of a development database and seeding it with test data.
3. Starting the server and syncing Sequelize models with the MySQL database.
4. Retrieving categories, products, and tags using GET routes.
5. Creating, updating, and deleting data in the database using POST, PUT, and DELETE routes.

## License

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)

## Contact

If you have any questions about this application, please contact me at jadyngg19@gmail.com and you can find more of my work on https://github.com/Jadyngg19.

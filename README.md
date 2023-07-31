# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Your Task

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

Your task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, you’ll also need to provide a link to a walkthrough video that demonstrates its functionality and all of the acceptance criteria being met. You’ll need to submit a link to the video and add it to the readme of your project.

## User Story

As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies, so that my company can compete with other e-commerce companies effectively.

Acceptance Criteria
Functional Express.js API: The application should have a functional Express.js API that can handle incoming requests and respond appropriately.

Database Connection: The API should be able to connect to a MySQL database using Sequelize, with the necessary database name, MySQL username, and MySQL password provided via environment variable file.

Database Creation and Seeding: The application should be able to create a development database and seed it with test data by running the appropriate schema and seed commands.

Server Start and Database Sync: The API should start the server and sync Sequelize models to the MySQL database when the application is invoked.

GET Routes: API should include GET routes for categories, products, and tags. When these routes are accessed via Insomnia, the data should be displayed in formatted JSON.

POST, PUT, and DELETE Routes: API should include POST, PUT, and DELETE routes for categories, products, and tags. When tested in Insomnia, these routes should allow successful creation, update, and deletion of data in the database.
```

## Mock-Up
![Screenshot 2023-07-31 165926](https://github.com/momofastorm/ORM-Challenge-E-commerce-Back-End/assets/127702972/1ba0a299-3b2b-48e1-b104-b0b24def0643)


The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)

Your walkthrough video should also show the POST, PUT, and DELETE routes for products and tags being tested in Insomnia.

## Getting Started

Getting Started
To set up the project, follow these steps:

Clone the repository.
Install the required dependencies using npm install.
Create the database using the schema.sql file in the db folder using MySQL shell commands.
Create a .env file in the root directory to store sensitive data like MySQL username, password, and database name as environment variables.
Database Models
The database should contain the following four models:

Category
id: Integer, primary key, auto increment.
category_name: String, doesn't allow null values
Dependencies
The project requires the following packages to be installed:

MySQL2: To connect the Express.js API to a MySQL database.
Sequelize: To interact with the MySQL database using Sequelize ORM.
dotenv: To use environment variables for sensitive data storage.
[Note: Please refer to the provided starter code and package.json file for more details on dependencies and scripts.]

Thank you for working on this project! If you have any questions or need further assistance, feel free to reach out.

Happy coding!
Marcy
marcyrappaport.blessed@gmail.com

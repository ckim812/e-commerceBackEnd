# e-commerceBackEnd

## Description

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. 

The goal of this project is to build the back end for an e-commerce site utilizing Express.js API to use Sequelize to interact with a MySQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Table of Contents

- [Link to video](#link-to-video)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Credits](#credits)

## Link-to-video

[https://app.castify.com/view/0d7c978a-6752-4ca4-a338-ee4dd79804a7](https://app.castify.com/view/0d7c978a-6752-4ca4-a338-ee4dd79804a7)

## Usage

```
Open the terminal.
Type "npm i" to install dotenv, Express, MySQL2, and Sequelize api's.

In the terminal from the "./db" directory, log into MySQL by typing "mysql -u root -p".
Enter your password.
Type "source schema.sql" to create the ecommerce database.

Exit MySQL.
Type "npm run seed" to seed the ecommerce database.

Log into MySQL again.
Type "show databases;" to show all databases.
Type "use ecommerce_db;" to select the ecommerce database.
Type "show tables;" to show available tables.
Type "select * from category;" to show a table of categories.
Type "select * from product_tag;" to show a table of product tags.
Type "select * from product;" to show a table of products.
Type "select * from tag;" to show a table of tags.


In the terminal, type "npm run watch" to start the server.
Open Insomnia.
To see current category data, type in http://localhost:3001/api/categories
To see current product data, type in http://localhost:3001/api/products
To see current tag data, type in http://localhost:3001/api/tags

Use the GET, POST, PUT, DELETE functions for each perform CRUD operations for each data set.
```

## Technologies-Used

```
dotenv, Express, MySQL2, and Sequelize api's
Node, terminal and Insomnia to view server interactions with database. 
```

## Credits

```
Created by Charles Kim.

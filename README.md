# eCommerce-back-end
An back end for my e-commerce website that uses the latest technologies

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

## Geting Started

* You will need to have mysql, and insomnia installed on your machine.
* Run "npm i" to install the dependent npm packages.

## Usage

The following walkthrough video shows how to initialise and seed and ecommerce database. The video shows how to launch the backend and use INSOMNIA to test GET, POST, PUT, and DELETE routes created for the product, tag, and category tables used by the ecommerce database.

[eCommerce backend walkthrough](https://drive.google.com/file/d/12k46c6JS7nVdeYCZfApjlTepJwgaR1RJ/view)

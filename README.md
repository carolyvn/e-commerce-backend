# Object-Relational Mapping (ORM): E-Commerce Back End

## Description
Build the back end for an e-commerce site by using Express.js API and Sequelize to interact with a MySQL database.

## Table of Contents
- [Installation](#installation)
- [User Story](#userstory)
- Acceptance Criteria
- [Demo](#demo)

## Installation
1. Clone the repo from Github
2. Install required dependencies with ```npm install```
3. Create an .env file and store your MySQL user and password in the file
4. Seed data to your database with 
   - ```mysql -u root -p```
   - ```source schema.sql```
   - ```npm run seed``
5. Run the app with ```npm start```

## User Story
    AS A manager at an internet retail company
    I WANT a back end for my e-commerce website that uses the latest technologies
    SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
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
    
## Demo
[part1](https://user-images.githubusercontent.com/90424035/159647925-65c40d25-c38b-431e-8f68-b912c2e408a3.mov)
[part2](https://user-images.githubusercontent.com/90424035/159647955-291adc5c-a590-4cb3-b4f8-278ff7eed089.mov)

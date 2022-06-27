# Homework-13-ORM
Create a mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.

<p align = "center">
<img alt="preview" src="./imgs/screenshot.png">
</p>

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
## E-Commerce Backend Demo 

Video Demo for the application: [Video](https://youtu.be/TS4lhvd99LE).
## Table of Contents

- [Homework-13-ORM](#homework-13-orm)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [E-Commerce Backend Demo](#e-commerce-backend-demo)
  - [Table of Contents](#table-of-contents)
  - [Resources](#resources)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Test](#test)
  - [License](#license)
  - [Questions](#questions)

## Resources

* [Node.js](https://nodejs.org/)
* [Inquirer.js](https://www.npmjs.com/package/inquirer)
* [MySQL](https://www.npmjs.com/package/mysql)

## Installation

* Git Clone the Repo into your system

* To install dependencies, run the following in your terminal:
  
`npm i`

`npm i mysql2`

`npm i sequelize`

`npm i dotenv`

* Edit `.env` file using your credentials
## Usage

* After installations are completed, run the app with: 

`mysql -u root -p`

Enter `password` when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

## Test

`npm test` = ```echo "Error: no test specified" && exit 1```
## License

* Copyright 2022 Philip Hwang
* This repository is licensed under the [MIT license](./LICENSE).

## Questions

If you have any questions, please contact me at: 
* Email: [pshwang93@gmail.com](mailto:pshwang93@gmail.com). 
* GitHub: [phwang93](https://github.com/phwang93).
* Repo: [Homework-13-ORM](https://github.com/phwang93/Homework-13-ORM).
* Video: [E-Commerce Backend Demo](https://youtu.be/TS4lhvd99LE).
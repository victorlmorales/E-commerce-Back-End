# E-commerce Back-End ![MIT license](https://img.shields.io/badge/License-MIT-blue.svg) ![Project Package Badge](https://img.shields.io/badge/package-Sequalize-informational) ![Project Package Badge](https://img.shields.io/badge/package-mysql2-informational) ![Project Package Badge](https://img.shields.io/badge/package-Express.js-informational)

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black)
![ExpressJS](https://img.shields.io/badge/Express.JS-000000?style=for-the-badge&logo=Express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)

## Table of Contents

* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Features](#features)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)
* [License](#license)
* [Credits](#credits)

## Description

  A MySQL back-end REST API for an e-commerce website. The API uses Express.js server to perform CRUD operations. Sequalize is used to interact with the MySQL database. Sequalize is a Node.js ORM(Object Relation Mapping) library.

## Installation

Follow these steps to install the necessities for the app

1. Make sure to have [Node.js](https://nodejs.org/en/download/) installed.

    * If you do not have Node.js installed follow [these instructions](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

2. To use this program you need to clone this repository using the following command:

    ```
    git clone git@github.com:victorlmorales/E-commerce-Back-End.git
    ```

3. Then you have to install all the dependencies.

    ```
    npm i
    ```

    * This will install the [MySQL2 Package](https://www.npmjs.com/package/mysql2), [Express.js Package](https://www.npmjs.com/package/express), [Sequalize Package](https://www.npmjs.com/package/sequelize), and [Dotenv package](https://www.npmjs.com/package/dotenv)

4. You also need to set up a .env file in the root directory in order to connect to your MySQL database.

    ```
    DB_NAME=example-db
    DB_PASSWORD=
    DB_USER=root
    ```

      * If you do not know how to set up MySQL server follow the [follwing instructions](https://dev.mysql.com/doc/mysql-getting-started/en/).

---

## Usage

Follow these steps to use the app

1. After downloading everything run the follwing command:

    ```
    mysql -u root -p 
    ```

    * This will prompt you to enter your mysql user password.

2. Once in the mysql shell, source the schema.sql file:
    ```
    SOURCE db/schema.sql;
    ```
    * This command will create the database in the schema.sql file

3. Leave the mysql shell by typing the follwing command:
    ``` 
    QUIT;
    ```

4. Once in the root directory of your project you have to seed the dadatbase with sample data:
    ```
    npm run seed
    ```

5. Now you can start up the server by running:
    ```
    npm start
    ```

6. You can use tools such as [Insomnia](https://docs.insomnia.rest/insomnia/get-started) to test the routes or feel free to go to http://localhost:3001/api/ in your browser to view the raw data.
## Features

* Creates categories, products, and tags

* View all categories, products, and tags

* Update the categories, products, and tags

* Delete the categories, products, and tags

* Creates relationships between the models

## Contributing

  N/A

## Tests

N/A

## Questions

  Have questions about this project?  
  GitHub: <https://github.com/victorlmorales>  
  Email: victor.l.morales2020@gmail.com

## Links

  [Demonstration Video](<https://drive.google.com/file/d/1-x4KK8dbiGOcFAB_jPS8H5di9LqCujpT/view>)

## License

    This project is licensed under the MIT license.

## Credits

  Victor Morales

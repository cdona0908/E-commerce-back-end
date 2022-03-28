# E-commerce-back-end

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

 ## Description

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

This application builds the back end for an e-commerce site. A working Express.js API was configured to use Sequelize to interact with a MySQL database created using models and associations. RESTful CRUD operations are shown in the walkthrough video using Insomnia.

## Installation

1. Clone the repository from GitHub. 
2. Run `npm i`  To install the neccesary dependencies:
   - dotenv: to use environment variables to store sensitive data, like your MySQL username, password, and database name.
   - express, mysql2 and sequelize: to connect to the database.
3. Run `mysql -u root -p` and enter your mysql password to connect to the database
4. Use the schema.sql file in the db folder to create your database using MySQL shell commands
5. Run `npm run seed` to seed data to the database
6. Run `npm start` to connect to the server 

## Usage  

Once the application is connected to the server, the user will be able to get, create, edit and delete categories, products and tags.

## Links

* Walkthrough video:

  https://drive.google.com/file/d/1RP4vn-yl_hTe5fp0Bq1Bu7BDmgpR1dJM/view

* The URL of the GitHub repository:

  https://github.com/cdona0908/E-commerce-back-end.git

## Programming Languages

  * NodeJS
  * JavaScript

## License

  This project is licensed under MIT license. 

## Contributing
  
  If you like to contribute to this application, please refer to the following guidelines:

  Please refer to the Contributor Covenant v2.1 in the following  website: https://www.contributor-covenant.org for guidelines details on how to contribute

## Questions

  You can find me on Github: [cdona0908](https://github.com/cdona0908) <br>
  Any questions? Email me to : celiamdona@gmail.com

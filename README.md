# E-Commerce-BackEnd

## Description

E-Commerce BackEnd is an e-commerce API using Express.js and Sequelize to interact with a MySQL database.

## Key Learning:

1. Async Javascript.
2. MySQL
3. Node.js
4. NPM packages msql2
5. Insomnia for API testing
6. Usage of Github (uploading and publishing on github).

## Table of Contents

- [Installation](#Installation)
- [Usage](#Usage)
- [License](#License)
- [Contributors](#Contributors)
- [Tests](#Tests)
- [Technologies](#Technologies)
- [Questions](#Questions)

## Installation

- Install MySQL on your machine.
- Clone project into a local directory and cd into the project directory.
- On console run npm install. It will install all project dependencies.
- In the projects root directory, you will need to create a file named ".env", to hold your MySQL password safely.For reference an example .env file is given.
- We can create Database Schema from MySQL shell by entering command <$ mysql -u root -p> and then enter your password when requested.
- Run the command <mysql source ./db/schema.sql> to create the database.
  To check whether ecommerce_db Database has been created or not we can use this command <mysql show databases;> to verify.
- Run the command <mysql exit> to return to the command line.
- Run the command < npm run seed> to seed the database with sample data.
- Run the command < npm run watch> to start the server.
- To interact with Database no front end is available so we need to make an api requests from an application like Insomnia or Postman.

## Usage

- Homepage Screenshot

  ![CLI](./images/screenshotInsomnia.jpg)

- Mockup

  [Watch Video](https://youtu.be/bzqA3CMndlI)

## License

- The application is covered under the license MIT. For more Info please visit [License Info](https://opensource.org/licenses/MIT)

## Contributors

- None

## Tests

- None

## Technologies

- Node.js
- Insomnia
- MySQL

## Questions

If you have any questions about project you can either contact me or visit my github profile.

Link to my Github: [Github](https://github.com/gunjanb)

Email address :[gunjanbhargava2021@gmail.com](mailto:gunjanbhargava2021@gmail.com)

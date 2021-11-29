# U Vote It

Created a voting application using mysql. For learning purposes only. Uses Node.js application to connect to a SQL isntance. Uses the CRUD method (create, read, update and delete) methods to work with persistent data. Uses SQL statements to establish relations between data using primary and foreign keys.

## Table of Contents

* [Setup](#setup)
* [Usage](#usage)
* [Contributing](#contributing)

## Setup
:floppy_disk:

Go to [Node's website](https://nodejs.org/en/) and follow the download instructions for your appropriate setup. NPM, or Node Package Manager, is the default package manager for Node.js. It is distributed with Node.js. Do not forget to npm init if you are using it for the very first time.

Check that your system has the following npm:
- [Node Package Manager](https://nodejs.org/en/)
  - Run `npm install` in order to install the following npm package dependencies as specified in the `package.json`.
  - This will also help install express on your system and manage any other dependencies in your script.
- [Express](https://www.npmjs.com/package/express)
  - Express is a back end web application framework for Node.js. Released as free and open-source software under the MIT License. Designed for building web applications and APIs. Many users use it as a standard server framework for Node.js.

Uses MySQL and MySQL2 tools for this application:

- [MySQL](https://www.mysql.com/)
  - Considered the most reliable, scaleable, and developer-friendly open source relational dtabase management system. It powers the back end of many popular social, streaming, and service web applications.
- [MySQL2](https://www.npmjs.com/package/mysql2)
  - An npm package for Node.js with a focus on performance. Connects Node.js applications to the MySQL database.

`npm init`

`npm install express`

`npm install express mysql2`

## Usage

:computer:

mySQL prompts:

`mysql -u root -p`

`USE election;`

Command-line prompts:

Run `npm start` in the command line to start the server.

## Contributing

:octocat:

[paperpatch](https://github.com/paperpatch)
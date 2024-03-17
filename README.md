# Library Management System

Library Management System is a full stack monolith web application build with Node.js, Express.js and MongoDB (and Bootstrap).

This app is build for practice purpose and available publicly, where user can view all books, popular books, recently added books, filter book by genres, and search book by title.

Some features requires user authentication to be available, such as accessing the book cart, borrowing book(s), view currently borrowed book(s), view their profile, and their borrow history.

User authenticated as admin can access the admin dashboard where admin can perform CRUD for books, view borrow history of all user, and view all user public information.

## Links

- [Repository](https://github.com/Kapileswar-Moharana/Library-Management-System?tab=readme-ov-file")

- [Live Demo](https://library-management-system-1-attg.onrender.com)

## Build With
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Bootstrap 5](https://getbootstrap.com/)

# Getting Started

## Prerequisites
These are the requirements to run this project.
- [Node.js v16+](https://nodejs.org/en/)
- [npm v8+](https://www.npmjs.com/)

## Installation

Clone this repository

```sh
git clone https://github.com/Kapileswar-Moharana/library-management-system.git
```

Change to the project directory
```sh
cd library-management-system
```

Install NPM packages
```sh
npm install
```

Duplicate .env.example file and rename it as .env and setup the envinronment variables
```sh
PORT=PORT_NUMBER
DB_URL=ENTER_YOUR_MONGODB_URL
JWT_PRIVATE_KEY=ENTER_YOUR_UNIQUE_JWT_PRIVATE_KEY
```

Run (development)
```sh
npm start
```
## Features

  * Robust routing
  * Focus on high performance
  * Super-high test coverage
  * HTTP helpers (redirection, caching, etc)
  * View system supporting 14+ template engines
  * Content negotiation
  * Executable for generating applications quickly

## Docs & Community

  * [Website and Documentation](http://expressjs.com/) 
  * [#express](https://webchat.freenode.net/?channels=express) on freenode IRC
  * [GitHub Organization](https://github.com/expressjs) for Official Middleware & Modules
  * Visit the [Wiki](https://github.com/expressjs/express/wiki)
  * [Gitter](https://gitter.im/expressjs/express) for support and discussion


### Security Issues

If you discover a security vulnerability in Express, please see [Security Policies and Procedures](Security.md).


## Contributing

[Contributing Guide](Contributing.md)





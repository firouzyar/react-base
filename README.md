# React Base Project

This project is a React application set up with TypeScript, ESLint, Prettier, and Docker. This README provides all the necessary instructions to run the app, lint and format the code, and run tests.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Linting and Formatting](#linting-and-formatting)
- [Testing](#testing)
- [Using Docker](#using-docker)

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (Version 16 or above)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/firouzyar/react-base.git
   cd react-base

   ```

2. Install the dependencies:

npm install
Running the Application
In the project directory, you can run:

## Running the Application

npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified, and the filenames include the hashes.
Your app is ready to be deployed!

## Linting and Formatting

To run ESLint and Prettier, use the following command:

npm run lint
This will lint the code according to the defined ESLint rules. If you want to automatically fix some of the issues, you can run:

npm run lint:fix
This command will fix the fixable issues in your code.

## Testing

To run tests, use the following command:

npm test

## Using Docker

To run the app in development mode with Docker:

Build and run the app using Docker Compose:
docker-compose up
This will start the app at http://localhost:3000 with hot-reloading enabled.

To run the app in production mode with Docker:

Build and run the app using the production setup:
docker-compose -f docker-compose.prod.yml up --build
The app will be served at http://localhost using NGINX.

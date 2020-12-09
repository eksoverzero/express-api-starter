# Express API Starter

A personal starter from mixed sources:

* [w3cj/express-api-starter](https://github.com/w3cj/express-api-starter)
* [feredean/node-api-starter](https://github.com/feredean/node-api-starter)

Includes API Server utilities:

* [morgan](https://www.npmjs.com/package/morgan)
  * HTTP request logger middleware for node.js
* [helmet](https://www.npmjs.com/package/helmet)
  * Helmet helps you secure your Express apps by setting various HTTP headers.
* [dotenv](https://www.npmjs.com/package/dotenv)
  * Dotenv is a zero-dependency module that loads environment variables from a `.env` file into `process.env`

Development utilities:

* [nodemon](https://www.npmjs.com/package/nodemon)
  * nodemon is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.
* [eslint](https://www.npmjs.com/package/eslint)
  * ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.
* [mocha](https://www.npmjs.com/package/mocha)
  * ☕️ Simple, flexible, fun JavaScript test framework for Node.js & The Browser ☕️
* [supertest](https://www.npmjs.com/package/supertest)
  * HTTP assertions made easy via superagent.

## Getting started

```shell
# Clone the starter
git clone --depth=1 https://github.com/eksoverzero/express-api-starter.git <project_name>

# Change directory
cd <project_name>

# Set the starter as the upstream (for merging in starter updates later on)
git remote remove origin

# Add the starter as an upstream
git remote add upstream https://github.com/eksoverzero/express-api-starter.git

# Add a new master/main
git remote add origin <project_repo>

# Install dependencies
npm install

# Copy the .env.example contents into the .env
cat .env.example > .env

# Run (development mode) the API
npm run dev
```

### Updating from the starter

```shell
git fetch upstream
git rebase upstream/master
```

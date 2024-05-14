# Not-a-Scam.com
 [![MIT license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://lbesson.mit-license.org/)

 [![NPM Express](https://img.shields.io/badge/NPM-Express-green.svg)](https://www.npmjs.com/package/express)
 [![NPM Postgres](https://img.shields.io/badge/NPM-Postgres-green.svg)](https://www.npmjs.com/package/pg)
 [![NPM Sequelize](https://img.shields.io/badge/NPM-Sequelize-green.svg)](https://www.npmjs.com/package/sequelize)
 [![NPM Dotenv](https://img.shields.io/badge/NPM-Dotenv-green.svg)](https://www.npmjs.com/package/dotenv)
 
## Description

We’ll take a working Express.js API and configure it to use Sequelize to interact with a postgreSQL database. This application won’t be deployed so i’ll show demo gifs below that demonstrates its functionality..

![13-orm-homework-demo-01](https://github.com/LockedJCE/Not-a-Scam.com/assets/163614828/f704354c-086e-42bd-84a7-f0d66054b8f9)

![13-orm-homework-demo-02](https://github.com/LockedJCE/Not-a-Scam.com/assets/163614828/cb3a47c8-33d2-4034-a8dc-6bc34c8997b6)

## Table of Contents
  * [Acceptance-Criteria](#acceptance-criteria)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Licenses](#licenses)
  * [Contributing](#contributing)
  * [Questions](#questions)
## Acceptance-Criteria
    GIVEN a functional Express.js API
    WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file
    THEN I am able to connect to a database using Sequelize
    WHEN I enter schema and seed commands
    THEN a development database is created and is seeded with test data
    WHEN I enter the command to invoke the application
    THEN my server is started and the Sequelize models are synced to the PostgreSQL database
    WHEN I open API GET routes in Insomnia Core for categories, products, or tags
    THEN the data for each of these routes is displayed in a formatted JSON
    WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
    THEN I am able to successfully create, update, and delete data in my database
  ## Installation
To get started clone this repository using 
<br>
```terminal
git clone git@github.com:LockedJCE/Not-a-Scam.com.git
```
Both Node.js and postgreSQL must be installed on your computer.

Install dependencies 
```terminal
npm init --y
``` 
```terminal
npm install
```
and then input the following in your terminal
```terminal
npm run seed
```
to start running application simply input 
```terminal
npm run start
```
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.
  ## Usage
   The application is used to GET data for each route(categories, products, or tags) as well as create, update, and delete data in those routes. It serves as the backend for an ecommerce site.
  ## Licenses
  This project is covered under the MIT license. To learn more about what this means, click the license button at the top.
  MIT License

    Copyright (c) 2024 Jensen

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
  ## Contributing
  Finished project so no contributions needed but thank you.
  ## Questions
    Have questions about this project?  
    GitHub: https://github.com/LockedJCE  


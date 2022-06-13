# Back End Shop

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

Back End Shop is the back end for an e-commerce site. It was written using JavaScript as a Node.js application. MYSQL was used for the server language, and Sequelize was used as the ORM. This programming will allow for a robust front end shop where products, product categories, and tags can be used to enhance the user experience.

## Links

[Code repository](https://github.com/wgrout87/Back-End-Shop)

[Application Demo](https://drive.google.com/file/d/1qIEStVu0V8P9-8cnpVMem6GUj2uzauFq/view)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

To install this project, first clone the repository. A file called simply ".env" needs to be created in the base directory. It requires the following data:

DB_NAME='ecommerce_db'

DB_USER='-your username here-'

DB_PW='-your password here-'

In the command line, from the base directory of the cloned repo, run the command, "npm i" to install the dependencies. Next in a MYSQL shell, run the command "SOURCE .\db\schema.sql;" to run the schema for this project. Then back in the command line, run the command "npm run seed" to seed the database with test data. At this point the project is ready to go, and can be started with the command "npm start".

## Usage

Currently there is no front end for use with this back end project. Several endpoints have been set up, however, that will allow for a variety of uses. There are GET routes for all categories, all products, and all tags, as well as single categories, single products, and single tags. There are also POST routes for adding new entries in each category, and PUT routes to modify existing entries. Finally there are DELETE routes to remove any unwanted categories, products, or tags. These routes are ready to use with front end development.

## License

Copyright 2022 William Grout

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

## Contributing

Any contributions to this open source project on GitHub are welcome. The standard fork and pull workflow that Git enables is the best way to contribute.

## Tests

Insomnia was used to test the functionality of the developed routes. With the application running it can be used to test all RESTful CRUD operations.

## Questions

My GitHub Profile: [https://github.com/wgrout87](https://github.com/wgrout87)

wgrout87@gmail.com

Please feel free to email me with questions. Mention the Back End Shop application in the subject line.

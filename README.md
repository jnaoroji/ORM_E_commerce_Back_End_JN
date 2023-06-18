# 13 Object-Relational Mapping (ORM): Jenny's E-Commerce Back End

## Description

My task is to build the back end for an e-commerce site by modifying starter code. I will configure a working Express.js API to use Sequelize to interact with a MySQL database. This is to increase my understanding of the fundamental architechture of E-commerce platforms.


## Usage

To use this application you will need to use Insomnia.
You will need to add my database name, MySQL username, and MySQL password to an environment variable file.
You will need to enter schema and seed commands. Then invoke the application and start the server.
You will be able to open API GET routes in Insomnia for categories, products, or tags.
The data for each of these routes is displayed in a formatted JSON.
You can also test API POST, PUT, and DELETE routes in Insomnia to successfully create, update, and delete data in my database.

Here is a link to the walkthrough video for my application: https://express-note-taker-jn.herokuapp.com/

## Credits

- [Fullstack Blog Video Submission Guide](https://coding-boot-camp.github.io/full-stack/computer-literacy/video-submission-guide)
- [Insomnia](https://insomnia.rest/download)
- [Insomnia](https://expressjs.com/)
- [MySQL2](https://www.npmjs.com/package/mysql)
- https://sequelize.org/docs/v6/core-concepts/assocs/#why-associations-are-defined-in-pairs
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [dotenv](https://www.npmjs.com/package/dotenv)

- Demos:
  GET routes tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

GET routes to return a single category, a single product, and a single tag in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The application's POST, PUT, and DELETE routes for categories in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
Please refer to the LICENSE in the repo or click on the badge for documentation.

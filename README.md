# Object-Relational Mapping (ORM) Challenge: E-commerce Back End

## Overview

This project is a demonstration of an Object-Relational Mapping (ORM) implementation for an E-commerce Back End. An ORM is a programming technique that allows developers to interact with a relational database using object-oriented programming concepts. In this challenge, we've created a back end for an E-commerce application, which includes models, routes, and a database that showcases the power of ORM in simplifying database interactions.

## Table of Contents

1. [Usage](#usage)
2. [Database Schema](#database-schema)
2. [Video](#video)
3. [Models](#models)
4. [Routes](#routes)
5. [Tests](#tests)
6. [Technologies Used](#technologies-used)
7. [Contributing](#contributing)
8. [License](#license)


## Usage

The E-commerce Back End provides a RESTful API with the following routes:

- `/api/products`: Retrieve all products or add new products.
- `/api/categories`: Retrieve all categories or add new categories.
- `/api/tags`: Retrieve all tags or add new tags.

You can use tools like [Insomnia](https://www.insomnia.rest) to test the API endpoints. The API allows you to create, read, update, and delete products, categories, and tags in the E-commerce database.

## Database Schema

You can find the SQL schema in the `db/schema.sql` file.

## Video 

[Walkthrough Video](https://drive.google.com/file/d/114npr4lmrFqefRBau3of0mE5_eQlqQa-/view)

![Alt text](<images/Screenshot 2023-11-02 193826.png>)
![Alt text](<images/Screenshot 2023-11-02 193834.png>)
![Alt text](<images/Screenshot 2023-11-02 193913.png>)


## Models

The ORM includes three models: `Product`, `Category`, and `Tag`, which are defined in the `models` directory. These models represent the data structure and relationships in the E-commerce application.

## Routes

The API routes are defined in the `routes` directory. Each route corresponds to a specific CRUD operation for products, categories, and tags.

## Tests

Unit tests are available for each model to ensure that the ORM functions correctly. You can run the tests using the following command:

```
npm test
```

## Technologies Used

- Node.js
- Express.js
- Sequelize (ORM)
- MySQL
- dotenv
- Jest (for testing)

## Contributing

We welcome contributions to this project. If you find any issues or have suggestions for improvements, please open an issue or create a pull request. For major changes, please discuss them first with the maintainers.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using our E-commerce Back End ORM project. If you have any questions or need further assistance, please don't hesitate to contact us.
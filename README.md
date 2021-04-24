# RESTful E-Commerce Back End Server

![Change to alt text](changeToImageLink)
## Description

This repository is a functioning back end server file for an e-commerce site. Express.js, Sequelize, and MySQL database technologies are the basis for this back end. By using this back end with front end code that provides and recieves JSON data, information can be easily stored across multiple MySQL tables that have communication facilitated between each other with this back end server.


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contribute](##contribute)
- [Test](##tests)
- [Contact](##questions?)

---

## Installation

To install necessary dependencies, run the following command:

    npm i

To install necessary seed data, run the following command afterwards:

    npm run seed

To install necessary MySQL data, run the following commands within a MySQL workbench:

    -- DROP DATABASE
    DROP DATABASE IF EXISTS ecommerce_db;

    -- CREATE DATABASE
    CREATE DATABASE ecommerce_db;

   
## Usage

To utilize the server, run the following command:

    node server.js


After running node server.js within an integrated terminal, the CRUD APIs may be hit by selecting /api/{products, categories, or tags}/{id for that specific product, category, tag} for all Create Read Update or Delete requests. Addionally, not including an id number for he endpoint on a GET request will simply display all data for the specified route (products, categories, or tag).

### Demo

[Click for a video demonstrating the functionality in more detail](https://drive.google.com/file/d/1ZvbxLg1bM7OlixsJE4jXFacsPYuW-GtG/view?usp=sharing)


![Change to alt text](changeToImageLink)

---  

## Contribute

None Applicable. Please contact me if you see any errors!

## Tests
To run tests, run the following command:

    node index

Afterwards, run the API routes you wish to test in Insomnia Core for categories, products, or tags.


## Questions?
If you come across any issues with the repo, please open an issue, or contact me directly at: anth8nyc@gmail.com. More of my work is avaiable on GitHub at [anth8nyc](https://github.com/anth8nyc/).


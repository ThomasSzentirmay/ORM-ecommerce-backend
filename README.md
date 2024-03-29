# ORM E-Commerce Backend

## Description

This application is the backend of an ecommerce site. It is connected to a MySQL database using the node package Sequelize, and stores data such as products, prices, tags and more. The application is built using ExpressJS, NodeJS and MySQL. Once the server is live, we can test all api routes to see the displays of data available.

![Screenshot 2023-07-12 194140](https://github.com/ThomasSzentirmay/ORM-ecommerce-backend/assets/132217664/fd4aca31-9a15-476f-ad08-b7dbf947941d)

Video Walkthrough: https://drive.google.com/file/d/1QN-gkLMcD4VelkqoZZFr_sJ189XmNQen/view?usp=sharing

## Installation

Users can clone this repository to their local machine. You will need to run 'npm i' in your terminal to get the necessary dependancies, and makes sure dotenv is installed as a dev dependancy. After that, you will need to enter your own MySQL details in the .env file.

## Usage

Once installed (instructions above), enter your MySQL shell. Run 'source db/schema.sql' to create the database, and then exit your MySQL shell. Then in your regular terminal, run 'node server.js' to start the server. Then visit 'localhost:3001' in your browser, and visit the desiried API routes to see the data.

## Credit

ChatGPT was utilized to debug, and fixes issues regarding .env configuration.

## License

MIT License

Refer to 'License' in the project repository for further information on the limitations and usability of this application under the MIT license applied to this project.

## Tests

Use Insomnia Core to test api routes for data.

## Features 

N/A

## Badges

N/A
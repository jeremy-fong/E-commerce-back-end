# E-commerce Back End 

## Table of Contents
1. [Title](#title)
2. [Project](#project)
3. [Description](#description)
4. [Installation](#installation)
5. [Usage](#usage)
6. [User Story](#user-story)
7. [Acceptance Criteria](#acceptance-criteria)
8. [Video Preview of Project](#video-preview-of-project)
9. [Source](#source)

## Title :
### E-commerce Back End 

## Project :
### *E-commerce Back End*

## Description :
* This project uses use MySQL2 and Sequelize packages to connect Express.js API to a MySQL database and dotenv package to use environment variables to store sensitive data.
* This project is the back end for an e-commerce site, which uses Sequelize to interact with a MySQL database. 

## Installation :
The user needs to install Node.js, npm dependencies, and MySQL.

## Usage :
- In the root directory terminal, install the npm dependencies with `npm install`.
- Then copy the .envEXAMPLE file and rename it to just `.env` and then input your MySQL password if you have one.
- Then seed the data by inputting `npm run seed` you will have to input your MySQL password once more if necessary.
- Once seeded, you can start the server with `npm start`.

## User Story :
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria :
```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```


## Video Preview of Project :
[Video Preview](https://drive.google.com/file/d/1y4iBZe7Pd3B55ZerlN10g_SOy867oJa4/view)

## Source :
- GitHub Link: https://github.com/jeremy-fong/E-commerce-back-end
# E-Commerce Backend

## Description
This project provides a functional backend to an ecommerce website. This app will display products data from an SQL database along with its associated categories and tags. The user can create, update, and delete new products, categories, and tags. The user can associate a product to a category and one or many tags.

## Video
[Demonstration Video](https://www.youtube.com/watch?v=McVWiRZ5CSA)

## Table of Contents
  - [Description](#description)
  - [Video](#Video)
  - [Instalation](#instalation)
  - [Usage](#usage)   
  - [Screenshot](#Screenshot)

## Instalation
  Run npm install for the project to function. Use mysql to source the database then use "npm run seed" to pre seed the app. Finally run npm start to add a listener on port 3001. It is reccomended to use insomnia or a similar program to test each of the routes.

## Usage
  Within insomnia or your program of choice, go to the correct local host. Each route is accessed using /api/*insert route here*/*optionally insert specific id here*. Get will display the seeded information. Post requests can be used to create new data. Put requests can modify attributes of existing data. And delete requests can remove an object by its ID.

## Screenshot
![Screenshot](https://github.com/Copernichris/employee_tracker/blob/main/SS.png)

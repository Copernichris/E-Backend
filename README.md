# E-Commerce Backend

## Description
This project provides a functional backend to an ecommerce website. This app will display products data from an SQL database along with its associated categories and tags. The user can create, update, and delete new products, categories, and tags. The user can associate a product to a category and one or many tags.

## Video
[Demonstration Video](https://www.youtube.com/watch?v=BWjbCf_ij8o)

## Table of Contents
  - [Description](#description)
  - [Video](#Video)
  - [Instalation](#instalation)
  - [Usage](#usage)   
  - [Screenshot](#Screenshot)

## Instalation
  Run npm install for the project to function. Use mysql to source the database then use "npm run seed" to pre seed the app. Finally run npm start to add a listener on port 3001. It is reccomended to use insomnia or a similar program to test each of the routes.

## Usage
  Within insomnia or your program of choice, go to the correct local host. Each route is accessed using /api/*insert route here*/*optionally insert specific id here*. Get will display the seeded information. Post requests can be used to create new data. Put requests can modify attributes of existing data. Delete requests can remove an object by its ID.

## Screenshots
![Screenshot1](https://github.com/Copernichris/E-Commerce_Backend/blob/main/DEMO/getAll.png)
![Screenshot2](https://github.com/Copernichris/E-Commerce_Backend/blob/main/DEMO/getOne.png)
![Screenshot3](https://github.com/Copernichris/E-Commerce_Backend/blob/main/DEMO/POST.png)
![Screenshot4](https://github.com/Copernichris/E-Commerce_Backend/blob/main/DEMO/PUT.png)
![Screenshot5](https://github.com/Copernichris/E-Commerce_Backend/blob/main/DEMO/DELETE.png)

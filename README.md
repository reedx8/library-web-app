# LibraryManagementWebService

A class project for the CS 465/565: Full Stack Web Development (Winter 2021) at Portland State University. A collaboration by [Patrick Niyongabo](https://github.com/pniyongabo), [Xavier Reed](https://github.com/reedx8), and [Huy Doan](https://github.com/huy26).

See demo here: https://library-management-service.herokuapp.com

### Introduction

A library management web service that maintains and organizes a user’s library books online, showing a book’s availability and providing other essential library services. 

### Tech Stack

This is a MERN (MongoDB, Express JS, React JS, and Node JS) web service for a library management system.

### Features
* Show availability: List and browse the books available to checkout from the library.
* Sorting:  Sort library books based on author, publish date, date added, etc.
* View by category: View by each book's category.
* View by authour: View be eachs book's author
* Check-in and Checkout: Allows users to check-in and check-out books from the library.
* Searching:  Search for books in library, searching with fields such as title, author, genre, etc.
  

### Instructions for Running the Application

##### Running the Express Server

```
cd library-management-server
npm install
npm start
```

##### Running the Front End React App

```
cd library-management
npm install
npm start
```
If the `npm install` command fails, try running `npm install --legacy-peer-deps`.

### Libraries
Below are the libraries that we used when developing this project:
* frontend: [mdbreact](https://www.npmjs.com/package/mdbreact), [bootstrap](https://getbootstrap.com/), [React bootstrap](https://react-bootstrap.github.io), [nuka-carousel](https://www.npmjs.com/package/nuka-carousel)
* backend: express, cors

### Tutorials
Below are the Tutorials we referenced when working on this project:
* https://mdbootstrap.com/docs/react/tables/pagination/
* https://www.freecodecamp.org/news/deploy-a-react-node-app-to/
* https://github.com/heroku/heroku-buildpack-nodejs/issues/385
* https://www.npmjs.com/package/nuka-carousel
* https://openlibrary.org/dev/docs/api/books











# Assignment
Author: Amir Jafari <jafari.work@gmail.com>

## Description

Shopping cart app build with MERN stack and using RESTful API design. Responsive front-end design done with Bootstrap, JWT used for authentication, database hosted on MongoDB ATLAS.

You can get and view the list of all products from the API, register, add products to cart, remove specific product or empty entire cart, ...


## Technologies & Tools

### Front-end:

* React
* Redux
* Redux-Thunk
* React-Router
* React Hooks
* Bootstrap
* Prettier
* Axios
* SASS - BEMIT standard
* JOI-browser (for validation)
* JWT

### Backend:

* Node/Express
* MongoDB/Mongoose
* JWT

## Database design

### Products

| id | name | price | available_quantity | is_donation | description
| --|---|---|---|---|---|
| 1 | Brownie | 0.65 | 48 | false | text...
| 2 | Muffin | 1 | 36 | false | text...
| 3 | Jacket | 4 | 30 | true | text...

### Users

| id | name | password |
| --|---|---|
| 1 | demo | 1234 

### Orders

| id | username | user_id | items |
| --|---|---|---|
| 1 | demo | 5fc8cbd9e125c9307af3442f | [{...}] 

## Installation and Usage

### Requirements:

* Node.js installed

### Steps:
1. Clone repo on your local machine:
```
$ git clone https://github.com/amirjafari1992/energia.ee.git
```
2. Install dependencies:
```
$ cd energia.ee
$ npm install
```
> If you had any error please remove <b>package-lock.json</b> and <b>node_modules</b> folder. Then run `npm i` again.

4. Running the API:
```
$ npm run api
```
6. Running the APP:<br/>
```
$ npm start
```
7. API now running on ```localhost:5000``` and App running on ```localhost:3000``` (usually)

## TODOs
#### General
- [x] Readme
- [x] Prettier
#### Back-end
- [x] Create Rest-API
- [x] Database
- [x] Model for orders, users, products
- [x] DB sources for MONGODB
- [x] Get Controllers
- [x] Authentication with JWT
- [ ] Saving the orders on DB
- [ ] Test
#### Front-end
- [x] State managing
- [x] Validation
- [x] Hooks
- [x] Responsive
- [x] Test only for reducer
- [x] Authentication
- [ ] Design

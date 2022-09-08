# Introduction

A Simple ToDo App is built using the MVC Architecture, we have also implemented "authorization" so folx can sign up, customize & personalize the app 

---

# Objectives

- It's an app created to understand how MVC concept and logins are added

---


# Packages/Dependencies used 

bcrypt, connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, validator

---

# Install all the dependencies or node packages used for development via Terminal

`npm install` 

`npm start` to use nodemon in development

---

- in MongoDB, create a database called 'todo' and a collection called 'todos'

---

# Things to add if using heroku for production

- Create a `.env` file and add the following as `key: value` 
  - PORT: 2121 (can be any port example: 3000) 
  - DB_STRING: `your database URI` 
 ---

 # if using a local host:
- .env file must be set up as follows:
  - PORT = num
  - DB_STRING = 'mongodbclientstring'



# Introduction

The project was built to take the hassle out of where to go in Las Vegas(can be changed to other cities) so that tourists can spend more time having fun and less time browsing the internet.
Initially developed implementing the MVC Architecture and "authorization" so users can sign up and personalize their experience.  


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



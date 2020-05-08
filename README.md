# Node-Express-Handlebars
HW13  Eat-Da-Burger! 

## Overview 
This is a simple burger logger with MySQL, Node, Express, Handlebars and a homemade ORM.  
The application is deployed on Heroku.

## Purposes 
- [x] Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.
- [x] Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page
- [x] The app will store every burger in a database, whether devoured or not.


## Directory Structure 

├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars

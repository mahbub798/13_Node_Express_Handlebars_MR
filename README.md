# Title of the project: Burger Time


  [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/mahbub798/13_Node_Express_Handlebars_MR)


### Description

The app lets users input the names of burgers they'd like to eat. This app will store burgers in a database, and uses handlebar to display the results.


### How to use the Application

1. In the text area type in the name of a burger that you would like to eat, and hit the 'Add Burger' button.

2. Burgers in the MySQL database will appear in the list named 'Burgers to be devoured'.

3. When you want to eat a Burger click 'Devour!' and the burger should move to the 'Burgers devoured' column.


### Technologies Used

* Node.js
* MySQL
* Node Packages (express, mysql, express-handlebars)
* Bootstrap


#### Directory structure

```
.
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
```

  # Questions

  If you have any questions about the repo, open an issue or contact mahbub798 directly mahbub798@gmail.com.
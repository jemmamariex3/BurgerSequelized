# BurgerSequelized
### Overview
I sequelized the a `Burger` app you made that I made with MySQL, Node, Express, Handlebars and a custom ORM last week. 

### Set Up
1. Created a new folder called `sequelizedBurger`
2. Copied the contents of the old Burger App
3. Ran `sequelize init` to create the neccesary sequel files.

#### Sequelized!

* Removed all references to your vanilla MySQL queries and replace them with Sequelize queries.

	* Edited new `config.json` file to include database configurations. Placed JawsDB details in the `production` property of json file; the details of local database go in the `developer` property.

	* Removed old ORM file, as well as any references to it in `burgers_controller.js`. Replaced those references with Sequelize's ORM methods.
## Copyright
Coding Boot Camp (C) 2016. All Rights Reserved.

# CRUDAPI-NodeJS and ExpressJS

Author: Etienne Selemani

Description : Project CRUDAPI-NodeJS and ExpressJS

STEPS TO FOLLOW

Step 1: Create Node js Application for Node js CRUD example

Step 2: Install Prerequisite for node js

Step 3: Create Database, Table, and Connection for node js CRUD example with MySQL

Step 4: Create CRUD Routes

Step 5: Crete View Files for CRUD example in node.js

Step 6: Run the index.js file


Step 1: Create Node.js Application for node.js crud example
    In this step, we will create a node.js application using the below commands.

        mkdir node_js_crud_operation

        cd node_js_crud_operation

        npm init

Step 2: Install Embedded JavaScript templates (ejs)
    In this step, we will install ejs using the below command :

        npm install ejs

Step 3: Install express.js in App
    Now, install express js using the below command.

        $ npm install express --save

Step 4: Install Dependency
    Next, we need to install some dependencies. So, copy the below command and paste it into your terminal

        # flash message:
        npm install express-flash --save

        # session like PHP:
        npm install express-session --save

        # to send PUT and DELETE requests:
        npm install method-override --save

        # driver to connect Node.js with MySQL:
        npm install mysql --save

Step 5: Create Database and Table for node js crud example with mysql
    Now, create a database and create a user's table.

        CREATE TABLE `users` (
        `id` int(50) NOT NULL,
        `name` varchar(100) DEFAULT NULL,
        `email` varchar(100) DEFAULT NULL,
        `position` varchar(100) DEFAULT NULL
        ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;


        ALTER TABLE `users`
        ADD PRIMARY KEY (`id`);

        ALTER TABLE `users`
        MODIFY `id` int(50) NOT NULL AUTO_INCREMENT;
        COMMIT;


I think this documentation related to the project will be useful to you, 
if not please leave us a message on gmail at etienneselemani47@gmail.com


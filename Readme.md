## sequelize library

** note **
 After running the server for the 1st time this is what you get in the console:
```
sequelize deprecated String based operators are now deprecated. Please use Symbol based operators for better security, read more at http://docs.sequelizejs.com/manual/tutorial/querying.html#operators node_modules/sequelize/lib/sequelize.js:242:13
App listening on PORT 8080
Executing (default): CREATE TABLE IF NOT EXISTS `books` (`id` INTEGER NOT NULL auto_increment , `title` VARCHAR(255), `author` VARCHAR(255), `genre` VARCHAR(255), `pages` INTEGER, `createdAt` DATETIME NOT NULL, `updatedAt` DATETIME NOT NULL, PRIMARY KEY (`id`)) ENGINE=InnoDB;
Executing (default): SHOW INDEX FROM `books`
```

# secure-login-system

::::This is for implementing very secure login system with PHP
:: Let's begin°

Navigate to your MySQL Serve and create a database named Authentication 
Copy the SQL command below and paste it in the SQL Tab on your PHPMyAdmin control Panel

CREATE TABLE `users` (
  `id` int(11) NOT NULL,
  ` first_name ` varchar(100) NOT NULL,
  ` last_name ` varchar(100) NOT NULL,
  ` password ` varchar(100) NOT NULL,
  `hash` varchar(100) NOT NULL)

After pasting this click GO

Now the database and the required table has been created
You can now navigate and start using the app
 login-system/index.php
You can start registering users and generally testing the app as you wish

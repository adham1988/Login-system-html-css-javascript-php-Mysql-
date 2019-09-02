# Login-system-html-css-javascript-php-Mysql-
Welcome to my login system example!

Just so you won't get confused looking at my files in this folder, I will let you know in which files you can find the different parts of the login system code :)

header.php
 - Here I start the "session" we need to have running, in order for the login system to remember that the user has logged in.
 - Here you will find the login and logout forms, that the user uses to log into the website.

includes/login.inc.php
 - Here we run the code that logs the user in, when they submit the login form in the header.
 - IMPORTANT! As you can see in this file, I have created the login system using Prepared Statements, which is NOT what we did in the video lesson! This is because you NEED to use Prepared Statements in order to make your login system safer. I have written comments inside the login script that explains what happens in detail ;)

signup.php
 - Here the user can sign up, if he/she doesn't have an account yet.

includes/signup.inc.php
 - Here we run the code that signs the user up in our database, when they submit the sign up form in signup.php.
 - I have ALSO used Prepared Statements here! And again I have left comments inside the sign up script that explains what happens in details ;)

index.php
 - Here we only display a message if the user is logged in.

includes/logout.inc.php
 - Here we simply run the logout script, when the user clicks the logout button in header.php

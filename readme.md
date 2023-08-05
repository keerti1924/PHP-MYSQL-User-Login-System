
<h1 style="color:blue;">PHP MySQL User Signup Login System</h1>

A login and signup form using HTML, PHP, and MySQL. This form allows users to register and login. 
All information is stored in a MySQL database. After successful login the user is redirected to their dashboard.
I enjoy making software so much! Please, if you see any issues make them known!

## Technologies Used
- `HTML`
- `CSS`
- `JavaScript`
- `Bootstrap5`
- `PHP`
- `MySQL`



## Files
- *home.php* -- The main page showed after login. Edit your own homepage.
- *index.php* -- The main page showed before login.
- *login.php* -- Login Page.
- *signup.php* -- Signup Page.
- *edit.php* -- Edit your profile.
- *logout.php* -- Logout to the dashboard page.

## Features

* Stores passwords in DB as hashes
* Easy logout via logout.php
* Passwords are hashed and stored (You can't view the original password of the user).
* Username and email validation is done.

## How to Use

- Download all the source files to your computer.
- Create a DataBase as login in phpMyAdmin.
- Create users table in phpMyAdmin.
- Change the username and password in connection.php file.
- Create four columns id, name, email, password in the users table.
- Or import the [login_system.sql](loginsystem.sql) file in the phpMyAdmin.
- Save the files, upload them to your webserver and give it a try.

## Preview

### Homepage
![screenshot](readme/index.jpg)

### Signup Page
![screenshot](readme/signup.jpg)

### Signin Page
![screenshot](readme/login.jpg)

### Dashboard Page
![screenshot](readme/dashboard.jpg)

### Update Profile Page
![screenshot](readme/update.jpg)

## License

This software is under an MIT License. Which allows full use to edit, distribute, or sell this code.
See the "LICENSE" file for more information!

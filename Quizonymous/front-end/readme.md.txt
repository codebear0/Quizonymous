Quizonymous - The Quizzing Site

Database Management Systems project which aims in providing a platform for organizations to conduct quiz competitions alongside providing a user-friendly quizzing experience to the users.

Go to the Documentation folder to view detailed description of the project.

--TABLE OF CONTENTS--
	1. INTRODUCTION 
	2. FUNCTIONAL REQUIREMENTS 
	3. ER DIAGRAM 
	4. RELATIONAL SCHEMA 
	5. USER INTERFACE DESIGN 
	6. IMPLEMENTATION
		a. CREATING AND CONNECTING TO DATABASE 
		b. TABLE CREATION 
		c. SETTING UP FOREIGN KEYS & CONSTRAINTS 
		d. SIGNING UP 
		e. LOGGING IN 
		f. TAKING QUIZ 
		g. SETTING UP TRIGGERS 
		h. SETTING UP PROCEDURES (WITH CURSORS) 
		i. SETTING UP VIEWS 
		j. FRONT END 
	7. RESULT 
	8. REFERENCES 

In order to use this application, download and install XAMPP from https://www.apachefriends.org/index.html
Download/Clone this repository into the hosting folder [var/www/html in 'Linux', htdocs in 'Windows'].

Open the XAMPP control panel and start Apache and MySQL.
Edit the config.php with your phpMyAdmin credentials (You can create your account by going into http://localhost/phpmyadmin/).

Now run build.php to setup the application.

After the successful completion of the aforementioned steps, the application is ready to be used.
Enter http://localhost/Quizonymous/front-end in your web browser to go to the home page.

If you wish to remove the database from your SQL server, run dropDB.php

--HAPPY QUIZZING--

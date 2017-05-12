# University Registrar

A university website that lists courses, instructors, and students.

This project features:
* A custom testing_module that includes:
* A simple Book Price calculator for students to add up the price of their books.  
* A Unit Test for said calculator.

* An article viewer that has been enabled with AJAX.  These articles provide students with help and hints during their life as a university student.

* A list of courses offered at this tiny university with the associated teachers, subjects, course names, and rooms they are held in.



## Technologies used:
- Local Drupal development environment.
- MAMP
- JavaScript
- PHPUnit Tests
- Drupal Web Tests

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [MAMP/LAMP/or WAMP](https://www.mamp.info/en/) (for Macs)
* [Drupal](https://www.drupal.org/)


### Usage

* Go to our Github repository
(https://github.com/ptown-epicodus/course-registrar)

* From your terminal:

* `git clone` this repository to your Desktop
* `cd course-registrar`

### Start MAMP

* Click on Preferences in your MAMP window and set your document root to the top level of your repository.

### Import the Database Dump
* Open phpMyAdmin and click on the "Import" tab.

* Leave all the default settings and make sure the character set is "utf-8".

* Click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file located in sites/db-backup folder.

### Create the Database User
* Create the database username/password that Drupal uses to store things in the database.

* After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".

* Select username and password.  "jp-project" for dbname, username, and password for all

* After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.

* Then click the "Go" button on the bottom left.


* Visit your app at [http://localhost:8888](http://localhost:8888).


&nbsp;
## Known Bugs
* No known bugs

Copyright (c) 2017 Jason Brown and Patrick McGreevy

This software is licensed under the GPL license

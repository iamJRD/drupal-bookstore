# Epic Books

#### By: Jared Beckler | Epicodus | April 22, 2016

This is a basic site built using Drupal to practice the use of Features, core/contributed modules, and more.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [MAMP](https://www.mamp.info/en/)

## Installation

* `git clone https://github.com/jaredbeckler/drupal-bookstore` this repository
* open MAMP and click "Preferences"
* go to the "Web Server" tab and change the document root to the project folder and start the MAMP server
* under phpMyAdmin click on the "Import" tab
* select the zipped database file from `sites/backup_db/` and click go
* after the database imports, click on `bookstore_db` in the database list and then click the "Privileges" tab
* next click the "Add User" link on the bottom and enter the username `admin_bookstore`, change the dropdown menu in host to `localhost`, then enter the password `bookstore`, and then click "Go" on the bottom of the page
* to view the site, use your web browser to navigate to localhost:8888
* admin username: `admin`
* admin password: `bookstore`

## Known Bugs

There are currently no known bugs.

## Support and contact details

If you have any issues, questions, ideas, or concerns contact me through GitHUb. If you would like to make a contribution to the code, feel free to do so and notify me by e-mail.

## Technologies Used

* GIT
* Drupal
* Drush

### License

Copyright &copy; 2016  |  Jared Beckler  |  Epicodus  |  Portland, OR

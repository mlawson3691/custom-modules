# Practice with Custom Modules

#### A Drupal 7 app with custom modules, December 2nd, 2016

#### By Mark Lawson

## Description

This application is an exercise in Drupal 7 creating a wide variety of custom modules. 

## Setup/Installation Instructions

* Clone the repository
* Start a server using MAMP (on Mac)
* Open the MAMP Preferences:
  * Set the document root to the project's root directory
  * Set the Apache Port to 8888 and the MySQL Port to 8889
* Set up the database:
  * In the browser, navigate to phpMyAdmin (localhost:8888/phpMyAdmin)
  * Select the "Import" tab along the top
  * Choose the .sql.zip file from the project located in sites/db-backup
  * Make sure character set is "utf-8"
  * Click "Go"
  * Select the "Privileges" tab along the top
  * Click "Add User" and enter the following credentials:
    * Username: maril
    * Host: Local
    * Password: maril
  * Click "go"
* Navigate your browser to localhost:8888
* Login with admin account:
  * Username: maril
  * Password: maril
* NOTE: Before committing again, be sure to export database and replace copy in sites/db-backup

## Known Bugs

There are no known bugs at this time.

## Support and Contact Details

Please report any bugs or issues to mlawson3691@gmail.com.

## Languages/Technologies Used

* Drupal 7.52
* MAMP
* MySQL

### License

*This application is licensed under the MIT license.*

Copyright (c) 2016 Mark Lawson

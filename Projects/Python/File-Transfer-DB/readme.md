### File Transfer Application with Database
***

#### Objective

This project was an extension of the [File Transfer GUI](/Projects/Python/File-Transfer-GUI) project. The continued scenario was that the GUI was successfully transferring files for employees, however the users have reported that they have had issues with knowing when the last file transfer was initiated and whether another file transfer is due or not for the last 24 hours. The new task is to track and display the last time the file check was performed.

#### Steps Taken

With the functionality of the GUI already built, all that was needed was to create and connect to a database that could track the time that each file check is run. The most recent time could then be retrieved from the database and displayed to users in the GUI. I used SQLite3 for the database. For this new functionality the program would connect to the database once opened and check for the last file check record. When the file transfer button is clicked the current time is then added as a new record to the database.

#### The Result

An improved GUI with database functionality! Who doesn't love that new feature smell? For the purpose of demonstrating this project, there is no pre-existing database for users, so each time the program is run it will create the database. What I really liked about this project was that I got to experience firsthand how building clean functions makes things easier for revision and additional functionality later on. By keeping functions nice and concise when you go to reuse them later it makes additional implementation a breeze. The bonus of adding database functionality to the GUI is that it opens up the opportunity for other functions. One feature I already thought of extending to this project is to also store records of all the individual files that are transferred during each file check.

[Return to portfolio](https://github.com/zfregin/portfolio)

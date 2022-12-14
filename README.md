# My-Books Project
This project contains a web application that allows a user to track reading progress. Users can log in with preset authentication profiles (see below), change the shelf of a book (To Read, Reading, Completed), favourite/unfavourite a book (automatically adds to Favourite Shelf), get recommended books based on the user's reading interests. 

If this project were to be continued, we would like to add a feature to remove a book from your library, complete the goals page, complete the statistics page, complete the settings page, improve the recommendation engine, add a feature to create and delete accounts, add a feature to search the book database to add to your account library and more...

## Development Environment

#### Set Up
1. From the command line, go to the root of the comp354-project folder and run the docker-compose up --build command. This will build and run all containers.
2. In your web browser, go to localhost:8080 to access Adminer. Login in with username = root, password = password, database = books
3. Once you're logged in, on the left side click the Import button. You can then upload the .sql files in this order: setup.sql > books_import.sql > data.sql. When you are uploading books_import.sql, make sure that the Stop on error checkbox is disabled.
4. Everything should be setup.

Frontend: localhost:3000
Express Backend: localhost:3001
Recommendation Backend: localhost:5000
Adminer: localhost:8080
MySQL: localhost:9906 

## Stack
##### Frontend: React.js, MUI, Tailwind, Axios
##### Backend (Primary): Express.js
##### Backend (Recommendation Engine): Flask
#### Database: MySQL

## Authentication

email: gabe@gmail.com
pw: password

OR 

email: Brandon@gmail.com
pw: password


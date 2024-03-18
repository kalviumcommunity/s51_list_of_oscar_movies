# Movie List CRUD Application with Firebase

This project is a CRUD (Create, Read, Update, Delete) application for managing a list of movies. It utilizes Firebase for secure data storage and authentication, allowing users to perform CRUD operations on the movies list. The security rules are configured to ensure that users can only update the data they have created and delete it.

## Technologies Used

- React
- Firebase

## Features

-Create new movies with details such as the title, release year, and whether the movie has won an Oscar or not.
- Read the list of movies.
- Update the details of movies that you have created.
- Delete movies that you have created.

## Restrictions

The application is designed to be used by users who are authenticated via email and password in Firebase Authentication. The following features are restricted
- You can only update or delete a movie if it is one that you have created yourself. 
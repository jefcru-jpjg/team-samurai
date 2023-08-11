
# Coding Exercise :running:

Build a RESTful API for a movie rental service. The API should allow users to browse available movies, rent movies, and view their rental history.

### Requirements:
* You can use any programming language and technology stack they prefer to implement the API.

* The API should handle the following entities:
	* _Movies_: Each movie has a unique identifier, a title, a genre, a release year, a rental price, and a number of copies available for rent.
	* *Users*: Each user has a unique identifier, a name, and an email address.
	* *Rentals*: Each rental has a unique identifier, a user, a rented movie, the rental date, and the due date (a week from the rental date).

### Functional Requirements:
* Implement an endpoint to retrieve a list of available movies with their details (title, genre, release year, rental price, and available copies).
* Implement an endpoint to allow users to register by providing their name and email address.
* Implement an endpoint to allow users to rent a movie by providing their identifier and the movie's identifier. The API should check if the movie is available for rent and update the movie's available copies and create a rental record.
* Implement an endpoint to retrieve a user's rental history, showing details of each rental they made, including the movie's details.

*Note*:
You may opt to host this API (preferred) if possible.
Please provide source (Github or similar) and necessary instructions on how to build and run your app.

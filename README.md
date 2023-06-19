# imdb-clone.github.io
IMDB Clone
A mini IMDB clone app that allows users to search for movies, view movie details, add movies to favorites, and manage their favorite movies list. The app utilizes the OMDB API to fetch movie data and provides a user-friendly interface for seamless movie exploration.

# Home Page ![home_page](https://github.com/pk1114585/imdb-clone.github.io/assets/45114125/1c39b87c-78e7-4ea5-b308-01321dd7731c)

# Movie Page
![movie_page](https://github.com/pk1114585/imdb-clone.github.io/assets/45114125/723eabc7-de9b-4c87-9ca3-b9878c97a968)


# Live Demo
Check out the live version of the app here: [Click here](https://pk1114585.github.io/imdb-clone.github.io/)

## Technologies Used
HTML
CSS
Bootstrap
Vanilla JavaScript
OMDB API - https://www.omdbapi.com/

## Installation and Setup
To run the app locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/pk1114585/imdb-clone.github.io.git
Open the index.html file in your preferred web browser.

# Usage
Enter a movie title in the search bar to search for movies.
As you type, search suggestions will appear below the search bar.
Click on a movie card to open the movie page with detailed information.
To add a movie to the favorites list, click on the favorite button on the movie card. The movie will be stored in the local storage.
To remove a movie from the favorites list, click on the delete button on the movie card.

# Code Structure
The code is organized into the following main files and directories:

index.html: The main HTML file that defines the structure of the app.
css/: Directory containing CSS stylesheets.
js/: Directory containing JavaScript files.
images/: Directory containing images used in the app.
API Key
To make the app functional, replace the placeholder API key with a valid OMDB API key. You can obtain an API key from the OMDB API website.

### Data
* suggestionList - an array which contains a list of movies based on searched keywords.
* favMovieArray - an array that gets movies from the local storage. 
* movieName - local Storage item which contains the name of clicked movie card.

### Functions (in code)
* fetchMovies
* addToSuggestionContainerDOM
* handleFavBtn
* addToFavDOM
* deleteMovie
* notify

# Acknowledgements
The app utilizes the OMDB API for movie data.
The Bootstrap CSS framework is used for styling the app.
License
This project is licensed under the MIT License.

Feel free to explore and contribute to the project. Any suggestions or improvements are welcome!

Enjoy exploring movies with IMDB Clone!

© 2023 [Pradeep kumar] | [GitHub Repository](https://github.com/pk1114585/imdb-clone.github.io) |

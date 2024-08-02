

Project Overview-
This project is an IMDb clone, a web application that allows users to search for movies, view detailed information about each title, and interact with a user-friendly interface. The application leverages the OMDb API to fetch movie data.

Features-
Movie Search: Users can search for movies by title.

Detailed Information: View detailed information about each movie, including poster, title, year, ratings, release date, genre, writer, actors, plot, and language.

Technologies Used-
Frontend: HTML, CSS, JavaScript
API: OMDb API

Installation--

Node.js (for running a local server, if necessary)
Git

Detailed Code Explanation-
index.html
This file contains the HTML structure of the application. It includes the search box, the search results container, and the movie details container.

Key Elements:

Search Container: Input field for searching movies.
Result Grid: Displays the detailed information of the selected movie.
style.css
This file contains the CSS styles for the application, ensuring a clean and user-friendly interface.

Key Styles:

Responsive Design: The application is responsive and adapts to different screen sizes.
Theme Colors: Dark theme with contrasting text and elements for better visibility.
imdb.js
This file contains the JavaScript code that handles the search functionality and data fetching from the OMDb API.

Key Functions:

loadMovies: Fetches movies based on the search term from the OMDb API.
findMovies: Initiates the search and displays the search results.
displayMovieList: Creates and displays the list of movies based on search results.
loadMovieDetails: Fetches and displays the detailed information of a selected movie.

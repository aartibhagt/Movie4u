## Movie4u - Your Movie Search Companion

Movie4u is a web application that allows you to search for movies using the OMDb API, view details, and add them to your favorites list. It's built using HTML, CSS, and JavaScript, providing a user-friendly interface for movie enthusiasts.

### Features

*   **Search Movies:** Easily search for movies by title using the search bar.
*   **View Movie Details:** Get basic information about a movie, including its title, release year, poster, and IMDb link.
*   **Add to Favorites:** Save movies to your favorites list for quick access later.
*   **View Favorites:** Browse your saved favorite movies on a separate page.
*   **Remove from Favorites:** Easily remove movies from your favorites list.
*   **Responsive Design:** Enjoy a seamless experience on different screen sizes, from desktops to mobile devices.

### Technologies Used

#### Frontend

*   **HTML:** Used to structure the web pages and display content.
*   **CSS:**  Provides styling and layout for the website, enhancing its visual appeal.
*   **JavaScript:** Handles user interactions, fetches data from the API, and dynamically updates the content.

#### API

*   **OMDb API:** Used to fetch movie data, including titles, descriptions, posters, ratings, and more. You will need a valid API key from OMDb to use this application.

### How It Works

1.  **Search:** Users enter a movie title in the search bar and click the "Search" button.
2.  **API Call:** JavaScript code sends a request to the OMDb API with the search query.
3.  **Data Fetch:** The API returns movie data in JSON format.
4.  **Data Display:** JavaScript parses the JSON data and dynamically creates HTML elements to display the movie information (title, poster, year) on the page.
5.  **Add to Favorites:** Users can click a "heart" icon to add a movie to their favorites. This information is stored in the browser's local storage.
6.  **View Favorites:** Users can navigate to the "Favorites" page to view their saved movies.
7.  **Remove from Favorites:** Users can remove a movie from their favorites list by clicking a "Remove" button next to the movie on the "Favorites" page.

### Installation and Usage

1.  **Clone the repository:** `git clone https://github.com/your-username/movie4u.git`
2.  **Replace API Key:**  Open `script.js` and replace `'f9994295'` with your actual OMDb API key.
3.  **Open index.html:** Open the `index.html` file in your web browser to run the application.

### Future Enhancements

*   **Pagination for Search Results:** Implement pagination to handle a large number of search results.
*   **More Detailed Movie Information:** Fetch and display additional movie details like the plot, actors, director, ratings, and reviews.
*   **Trailers and Previews:** Integrate movie trailers or previews for a more engaging experience.
*   **User Authentication:** Allow users to create accounts and manage their favorites lists.

This README file provides a basic overview of the Movie4u web application. Feel free to expand it with more specific details, code examples, or screenshots to enhance its clarity and usefulness.

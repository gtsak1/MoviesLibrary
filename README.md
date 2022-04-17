This android app uses The Movie Database API (https://developers.themoviedb.org/3/getting-started/introduction) in order to display lists of movies. Categories "Now Playing" and "Popular" are presented in two tabs with ViewPager. Pagination (endless scrolling) is performed in order to load more movies.

User can click on a movie and view details, like title, overview, release date, images and rating. User also has the ability to search for a movie.

MoviesLibrary app follows MVP architecture and AsyncTask is used for handling the data from the api.

Replace API_KEY in strings.xml with your API key.

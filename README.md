# usePopcorn Movie Rating App

usePopcorn is a movie rating app that allows users to search for movies, view details, and rate movies using a star rating system. It also keeps track of the movies you've watched and displays statistics about your watched movies.

## Features

- Search for movies using the OMDB API
- View detailed information about selected movies
- Rate movies using a star rating system
- Keep track of watched movies
- View statistics about your watched movies, such as average IMDb rating, average user rating, and average runtime

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/usepopcorn.git
   ```

2. Navigate to the project directory:

```bash
cd usepopcorn
```

3. Install the dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

5. Open your browser and go to http://localhost:3000 to see the app in action.

## Usage
- Use the search bar to search for movies.
- Click on a movie to view its details.
- Rate the movie using the star rating system.
- Add the movie to your watched list.
- View statistics about your watched movies in the "Movies you watched" section.

## Components
App
- The main component that handles the state and renders the app layout.

Loader
- Displays a loading message when data is being fetched.

ErrorMessage
- Displays an error message when there is an error fetching data.

NavBar
- The navigation bar that contains the logo, search bar, and number of results.

Logo
- Displays the app logo.

Search
- Handles the search input and allows users to search for movies.

NumResults
- Displays the number of search results found.

Main
- The main container for the app layout.

Box
- A container component that can be toggled open and closed.

MovieList
- Displays a list of movies based on the search results.

Movie
- Displays a single movie item in the movie list.

MovieDetails
- Displays detailed information about a selected movie, allows the user to rate the movie, and add it to the watched list.

WatchedSummary
- Displays statistics about the watched movies.

WatchedMoviesList
- Displays a list of watched movies.

WatchedMovie
- Displays a single watched movie item in the watched movies list.

StarRating
- A star rating component that allows users to rate movies.

## Custom Hooks

useKey
- A custom hook that handles keypress events.

useLocalStorageState
- A custom hook that manages state with localStorage.

useMovies
- A custom hook that fetches movies based on the search query.

## Styling
The app uses CSS variables for theming and a simple, modern design.

## API Key
The app uses the OMDB API to fetch movie data. Replace the KEY variable in the App component with your own OMDB API key.
  

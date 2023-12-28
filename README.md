# MovieCorn 🍿React App

This repository houses the **MovieCorn React App**, a project designed and developed by Sajal Timilsina. MovieCorn utilizes **React** for its frontend architecture to create an interactive movie browsing and tracking platform.

## Introduction

MovieCorn is a single-page application (SPA) built using **React** and various custom hooks to access and display movie data fetched from the [OMDb API](https://www.omdbapi.com/). It allows users to search for movies, view details, rate them, and maintain a personal watch list.
 - Hosted on: https://moviecorn13.netlify.app/

![image](https://github.com/SajalTimilsina/moviecorn/assets/19229631/a66a306e-c7e2-4b36-b351-d642aa58d618)


## Getting Started

### Installation

To run this application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/sajaltimilsina/moviecorn.git

2. Navigate into the project directory:
   
   ```bash
   cd moviecorn
  
3. Install dependencies:

   ```bash
   npm install

## Available Scripts

In the project directory, you can run:

- `npm start`: Runs the app in development mode.
- `npm run build`: Builds the app for production.
- `npm test`: Launches the test runner.
- `npm run eject`: Removes the single build dependency from the project.

## Dependencies

The MovieCorn React App utilizes several key dependencies:

- **React** and **React-DOM** for building the user interface.
- **Create React App** to bootstrap the project.
- **@testing-library** for testing components and interactions.
- **gh-pages** for deploying the app to GitHub Pages.

## Features

### Custom Hooks

The application implements various custom hooks for managing state and handling specific functionalities:

- **useMovies**: Fetches movie data from the OMDb API based on the user's query.
- **useLocalStorageState**: Manages the state of watched movies, storing data in local storage.
- **useKey**: Listens for specific key presses and triggers actions accordingly.

### Components

The app is composed of several components responsible for rendering different parts of the user interface:

- **NavBar**: Displays the application's navigation bar.
- **Logo**: Renders the MovieCorn logo.
- **Search**: Allows users to search for movies using a search input field.
- **NumResults**: Shows the number of search results.
- **Loader**: Indicates when data is loading.
- **ErrorMessage**: Displays an error message if data fetching encounters issues.
- **Main**: Main container for the app's content.
- **MovieList**: Renders a list of movies based on the search query.
- **MovieDetails**: Displays detailed information about a selected movie.
- **WatchedSummary**: Shows summarized statistics about watched movies.
- **WatchedMovieList**: Renders a list of watched movies.
- **StarRating**: Enables users to rate movies using a star rating system.

## Usage

Upon launching the application, users can:

- Search for movies using the search bar.
- View a list of movies based on the search query.
- Click on a movie to view its details, rate it, and add it to the watched list.
- Access a summary of watched movies and their statistics.

## Contributing

Contributions to MovieCorn are welcome! If you'd like to contribute, feel free to open pull requests or issues on the GitHub repository.

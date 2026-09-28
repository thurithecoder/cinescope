# CineScope 🎬

CineScope is a Flutter Android application that helps users discover movies, explore movie information, and organise a personal watchlist.

Built as an academic project for an Android Programming course.

## Features

- Search for movies, series, and episodes by title.
- Search for actors and actresses and explore their movie appearances.
- View movie details, including plot, release year, genre, cast, and ratings.
- Find official movie trailers on YouTube.
- Save movies to a personal watchlist stored on the device.
- Browse a curated selection of movies.
- Enjoy a Material 3 dark interface.

## Technologies

- Flutter and Dart
- Riverpod for state management
- GoRouter for navigation
- OMDb API for movie information and ratings
- TMDB API for actor searches and movie credits
- Local storage for the watchlist

## API Configuration

CineScope requires an OMDb API key for movie information and a TMDB v3 API key for actor and actress searches.

Create an `omdb.env.json` file in the project root:

{
  "OMDB_API_KEY": "YOUR_OMDB_API_KEY",
  "TMDB_API_KEY": "YOUR_TMDB_API_KEY"
}

Keep this file out of version control. Never commit real API keys to a public repository.

## Running the App

With Flutter installed and an Android device or emulator connected:

    flutter pub get
    flutter run

Rebuild the app after changing API keys.

## Project Scope

CineScope is a movie discovery application. It provides movie information and links to trailers; it does not host or stream full movies.

This project is intended for educational, non-commercial use.

## Attribution

Movie information and ratings are provided by OMDb.

Actor information and movie credits are provided by TMDB.

This product uses the TMDB API but is not endorsed or certified by TMDB.

## Project Status

Under active development.

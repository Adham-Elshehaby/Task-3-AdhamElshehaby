# Task-3-AdhamElshehaby

# Project 3: AI Recommendation Logic

## What it does
This project contains a few sample movies in a list called "movies". It takes 3 inputs from the user: Movie Genre, Movie Mood, and Movie Length. It then compares the user input to the corresponding movie data, and recommends the matching movie/movies to the user.

## How it runs
To run this program, type: python "project 3" in the terminal.

## How it works
The available movies are contained in a list called "movies". Fisrt, the user is prompted to pick a genre from a selection of available genres. If the genre the user selects is not one of the available genres, or if the user makes a mistake while typing the genre, an error message pops up, and the user is prompted to type the genre again. The same process goes for the movie mood. The user is then asked to pick the minimum and maximum movie length he would prefer, so that movies within this range can be given priority. Genre, Mood, and Length are the 3 variables being considered for each movie. If a movie satisfies 2/3 of these conditions, that movie, along with it's rating, is then appended to a list called recommendations. Then finally, the program prints all available movies matching the criteria. If no movies are found matching the criteria, a suitable message is also printed for that case.

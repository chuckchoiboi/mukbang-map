# Mukbang Map

## Description

This is a simple map that uses Google Map's API to locate local restaurants and provide recommendations based on the ranking logic and the user input.

## Features

There are two main features in the app.

- Feature 1: Restaurant Search

  - This feature uses Google Map's API and user location to find restaurants in the area and fetch the data to the app
  - The app will use the fetched data and combine it with the user rating information from the DB to show the listing
    - The listing gives an option to filter the restaurants that were visited the last 7 days
    - The listing positively ranks the restaurants with high average rating from the past visits
  - From the listing, user can select/deselect the restaurants to randomly select the restaurant

- Feature 2: Restaurant Rating
  - This feature locates the user and give a list of restaurants that are nearby
  - User can select the restaurant from the list and rate the restaurant postive or negative (thumbs up/down)

## Getting Started

### Tech Stacks

- Front-end: Flutter
- Database: SQL

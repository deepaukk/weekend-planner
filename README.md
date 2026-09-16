# Weekend Planner

A lightweight web app for finding activities based on available time, energy level, and weather.

## What it does

The app lets users:

- Set how much time they have available
- Select their current energy level
- Select the current weather
- Get activities ranked by how well they match
- Add their own activities
- Store activities locally in the browser
- Remove activities from their list

## How matching works

The recommendation system uses a simple rule-based scoring model.

Activities are scored based on:

- Time compatibility
- Energy-level compatibility
- Weather compatibility

Activities that require more time than the user has available are excluded.

The remaining activities are sorted by their calculated score, with the strongest matches shown first.

## Technologies

- HTML
- CSS
- JavaScript
- Browser localStorage

## Purpose

This was a personal project built to practice front-end development, JavaScript logic, and building a small interactive web application.

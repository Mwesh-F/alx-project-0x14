# ALX Project: 0x14 - Reading API Documentation

This project demonstrates how to understand and consume a third-party API by carefully reviewing its documentation. The focus is on the **MoviesDatabase API**, and how to structure API requests and handle responses effectively in a TypeScript-based application.

## API Overview

The **MoviesDatabase API** provides access to a wide variety of movie-related data. It allows developers to fetch lists of movies, retrieve detailed information about specific titles, search by keywords, filter by genre or year, and paginate results. This API is ideal for building movie discovery or catalog applications.

## API Version

**Version:** v1

## Available Endpoints

- **GET /titles**  
  Retrieves a list of movie titles. Supports filters such as genre, release year, and sorting options.

- **GET /titles/{id}**  
  Fetches detailed information about a specific movie title by ID.

- **GET /genres**  
  Returns a list of available genres for filtering.

- **GET /years**  
  Provides a list of available release years.

- **GET /search**  
  Performs a keyword-based search across all available movie titles.

## Request and Response Format

### Sample Request

```http
GET /titles?year=2021&genre=Action&page=1 HTTP/1.1
Host: moviesdatabase.p.rapidapi.com
X-RapidAPI-Key: YOUR_API_KEY
X-RapidAPI-Host: moviesdatabase.p.rapidapi.com

# Netflix TV Shows and Movies Analysis (SQL Project)

## Project Overview

This project, **Netflix-TV-Shows-and-Movies-SQL**, involves analyzing Netflix's vast catalog of TV shows and movies using SQL. The project utilizes two main datasets: `titles` and `credits`, which contain details about various shows and movies, such as genre, release year, cast, crew, IMDb scores, and other metadata.

This analysis aims to answer questions about popular genres, top-rated content, key contributors, and trends over the years. SQL queries are used to explore and extract insights from these datasets.

## Datasets

### 1. Titles
This dataset provides details about each title (movie or TV show) available on Netflix. It includes:
- **id**: Unique identifier for each title
- **title**: Name of the title
- **type**: Indicates whether the title is a movie or a TV show
- **description**: A brief synopsis of the title
- **release_year**: Year of release
- **age_certification**: Age rating of the title
- **runtime**: Length of the title in minutes
- **genres**: Genres associated with the title (e.g., Action, Drama)
- **production_countries**: Countries where the title was produced
- **seasons**: Number of seasons (for TV shows)
- **imdb_id**: IMDb identifier
- **imdb_score**: IMDb rating score
- **imdb_votes**: Number of votes on IMDb
- **tmdb_popularity**: Popularity score on TMDB (The Movie Database)
- **tmdb_score**: TMDB rating score

### 2. Credits
This dataset lists the cast and crew associated with each title.
- **person_id**: Unique identifier for each person
- **id**: Title identifier (matching `id` in the `titles` dataset)
- **name**: Name of the person
- **character**: Character portrayed (for actors)
- **role**: Role of the person (e.g., Actor, Director)

## Project Goals

The primary goals of this project include:
- **Genre Analysis**: Identifying the most popular genres on Netflix.
- **Top-Rated Content**: Finding titles with the highest IMDb and TMDB scores.
- **Contributor Analysis**: Identifying key actors, directors, and other contributors across Netflix's catalog.
- **Trends Over Time**: Analyzing how content has evolved over the years in terms of genres, types, and popularity.
- **User Preferences**: Determining viewer preferences based on age certifications, runtime, and genres.

## SQL Analysis

This project uses SQL to perform various analyses, including:
1. **Top 10 Most Popular Titles**: Querying the titles dataset for the highest-rated or most popular content.
2. **Genre Distribution**: Analyzing the distribution of different genres across the catalog.
3. **Content Type Split**: Analyzing the split between movies and TV shows.
4. **Most Frequent Contributors**: Listing the top actors, directors, and other contributors in the Netflix library.
5. **Yearly Releases**: Tracking the number of releases each year and identifying trends.
6. **IMDB and TMDB Ratings Comparison**: Comparing IMDb and TMDB ratings for insights on viewer and critic ratings.

## Project Files

- **movies_analysis.sql**: Contains all SQL queries used to extract insights from the datasets.
- **README.md**: Project documentation (this file).

## Technologies Used

- **SQL**: Used for data extraction, transformation, and analysis.

## Future Improvements

Potential future enhancements include:
- Incorporating additional datasets, such as viewer demographics or streaming duration.
- Adding visualization of the analysis for easier insights.
- Expanding the analysis to cover other streaming platforms for comparative insights.


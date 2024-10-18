# IMDB Scores Analysis 
<div align="center">
  <img src="https://github.com/user-attachments/assets/26b797f9-b74c-4ec3-bbe6-781c0483eaa7" alt="IMDB Scores Analysis " width="400"/>
</div>

## Project Overview

This project aims to analyze movie data from the IMDB database to uncover insights into movie scores, factors that contribute to high ratings, and trends across different genres and release years. By analyzing various attributes such as genres, duration, directors, and actors, this project provides an in-depth understanding of patterns in movie ratings and how certain characteristics may influence a movie's score.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Data Sources](#data-sources)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Visualizations](#visualizations)
- [Dashboard](#Dashboard)
- [Results](#results)


## Objectives

1. Clean and preprocess the raw IMDB dataset.
2. Perform exploratory data analysis (EDA) to uncover key patterns and trends in movie ratings.
3. Analyze the relationship between IMDB scores and various factors such as genre, year, and duration.
4. Create visualizations that highlight insights related to top-rated movies and genre-specific trends.
5. Provide actionable recommendations for filmmakers or content creators based on data insights.

## Technologies Used

- Excel
- Power BI

## Project Structure

```
/imdb-scores-analysis
├── data/               # Raw and cleaned IMDB dataset with dashboard
├── README.md           # Project overview and instructions
```

## Data Sources

The dataset used for this project is based on publicly available IMDB movie data, which includes:
- **Title:** The name of the movie.
- **IMDB Score:** The average user rating of the movie.
- **Genres:** The genre classification of the movie.
- **Director:** The director of the movie.
- **Release Year:** The year the movie was released.
- **Duration:** The length of the movie in minutes.

The dataset can be found in the directory in CSV format.

## Data Cleaning

Before performing any analysis, the data was cleaned to ensure accuracy. The steps included:
- Handling missing values in critical columns such as IMDB score, genres, and release year.
- Removing duplicates and inconsistent entries.
- Correcting data types for numerical columns such as duration and release year.
- Splitting multi-genre entries to analyze individual genres.

## Exploratory Data Analysis (EDA)

The EDA focused on understanding:
- **Score Distribution:** Distribution of IMDB scores across all movies.
- **Genre Breakdown:** Which genres tend to receive higher scores.
- **Release Year Trends:** How movie ratings have evolved over time.
- **Top-rated Directors and Actors:** Examining individuals frequently associated with high-scoring movies.

## Visualizations

The following visualizations were created to communicate insights from the data:
- **Score Distribution:** A histogram showing the spread of IMDB scores.
- **Genres vs. Scores:** A box plot comparing scores across different genres.
- **Release Year vs. Average Score:** A line chart showing the trend of average movie ratings over the years.
- **Top 10 Directors:** A bar chart showing the directors with the highest average IMDB scores.
- **Movie Duration vs. Score:** A scatter plot visualizing the relationship between movie duration and score.

## Dashboard
![Screenshot 2024-10-18 173756](https://github.com/user-attachments/assets/254ded6a-545c-4a24-a210-cf215af3fadd)


## Results

The project revealed several key insights into movie ratings:
- **Genres like Drama, Documentary, and History** tend to receive higher IMDB scores.
- **Movies released in the 1990s and early 2000s** show a notable increase in average ratings compared to earlier decades.
- **Top-rated directors** often have recurring genres, with some directors specializing in critically acclaimed films.
- **Duration vs. Score:** While longer movies tend to have higher ratings, there is an optimal range of around 120-150 minutes.

These insights provide useful guidance for filmmakers, content producers, and movie enthusiasts.

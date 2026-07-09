# Movie Recommendation System

A movie recommendation system built using Python and Streamlit that suggests similar movies based on content. The application uses the TMDB API to fetch and display movie posters for the recommended movies.

## Overview

This project recommends movies similar to the one entered by the user using a content-based recommendation approach. Users can enter a movie name, click the **Recommend** button, and view a list of recommended movies along with their posters.

## Features

- Search movies by name
- Get content-based movie recommendations
- Display movie posters using the TMDB API
- Simple and interactive Streamlit interface

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Pickle
- TMDB API

## Project Structure

```
movie-recommender-system/
├── app.py
├── movies.pkl
├── requirements.txt
└── README.md
```

> **Note:** The `similarity.pkl` file is not included in this repository because it exceeds GitHub's file size limit. You will need to generate it locally before running the application.

## Installation

Clone the repository:

```bash
git clone https://github.com/codewithtisha/movie-recommender-system.git
```

Go to the project directory:

```bash
cd movie-recommender-system
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## Usage

1. Enter the name of a movie.
2. Click the **Recommend** button.
3. View the recommended movies and their posters.

## Screenshots



## Future Improvements

- Improve recommendation accuracy
- Add genre and language filters
- Display movie ratings and release dates
- Deploy the application.